TypeBeat - Agnostic parsing of the `Content-Type` in OCaml
==========================================================

TypeBeat is a pure implementation of the parsing of the `Content-Type`'s value
(see [RFC822](https://tools.ietf.org/html/rfc822)
and [RFC2045](https://tools.ietf.org/html/rfc2045)). The reason of this *light*
library is to compute a complexe rule. Indeed, it's __hard__ to parse the value
of the `Content-Type`, believe me.

So it's a common library if you want to know the value of the `Content-Type` and
don't worry, we respect the standard. We saved
the [IANA](https://www.iana.org/assignments/media-types/media-types.xhtml)
database too.
