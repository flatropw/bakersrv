# bakersrv
L7T3 net/http practice
- Web server, responds to “/” (404 on any other request)
- Support POST and GET methods
- On GET request returns HTML page, containing FORM with name and address fields + submit button.
- Also there is a placeholder to display token on this page.
- On POST request reads name+address from body and creates a token as “name:address”.
- Then saves this token to Cookies
- Page reloads, token value displayed on page
