# node-nodemailer-lambda

## Intended as a thin wrapper for forwarding mail to IronPort 

This is mostly boilerplate from https://nodemailer.com and parameterizing the mailOptions object to get the input from the POST

### SAMPLE POST

``` json
{
  "from": "Mr.Sender@PureEvil.com",
  "to": "Stanley.S@Idontknowhowemailworks.com",
  "subject": "Mail From Lambda",
  "text": "woo?"
}
```