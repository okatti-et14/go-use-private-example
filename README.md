# go-use-private-example
```
GITHUB_TOKEN=ghp_XXX
git config --local url."https://$GITHUB_TOKEN:x-oauth-basic@github.com/".insteadOf "https://github.com/"
go env -w GOPRIVATE="github.com/okatti-et14/go-private-example"
```
