```
{{ range $key, $value := .Params }}
    {{ printf "%#v = %#v" $key $value }} <br/>
{{ end }}
```
https://discourse.gohugo.io/t/solved-how-to-view-all-page-params-including-front-matter-key-names-for-debug/9200/3