curl --request POST \
     --url https://api.easee.com/api/accounts/login \
     --header 'accept: application/json' \
     --header 'content-type: application/json' \
     --data '
{
  "erkka@sahkoasennuslouhi.com": "string",
  "Erkka123": "string"
}
'
