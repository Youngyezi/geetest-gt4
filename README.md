# geetest-gt4
极验 (geetest) gt4 版本


## install ##

```bash

go get -u github.com/youngyezi/geetest-gt4

```

## usage ##
```golang

req := geetest.Req{
    "lot_number":     lot_number,
    "captcha_output": captcha_output,
    "pass_token":     pass_token,
    "gen_time":       gen_time,
}

client := geetest.New(captchaID, captchaKey)

if err := client.Validate(req);err != nil {

}

```


