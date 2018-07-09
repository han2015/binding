# binding
gloang binding tool, extracted from `gin-gonic/gin` binging package. but replace the validator to `github.com/asaskevich/govalidator`.

To bind a `request body` into a type, use `model` binding. We currently support binding of `JSON, XML and standard form values` (foo=bar&boo=baz).
