client_ajax_logger
==================

Sending client-side logs with ajax. Depends on [Console Proxy](https://github.com/bermi/console-proxy).

**It's library-agnostic. You don't need jQuery.**


## Usage

Download source and add those scripts at the top of your HTML document (as first two scripts):

```
<script src="path_to_js/console-proxy.min.js" type="text/javascript"></script>
<script src="path_to_js/client_ajax_logger.js" type="text/javascript"></script>
```

* Change endpoint url in code

And that's all. Should work!

## Format of log entry

```json
{
  "agent": "Mozilla/5.0 (X11; Linux x86_64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/35.0.1916.114 Safari/537.36",
  "date": "2014-06-03T13:04:46.372Z",
  "message": "loaded: locales/en/translation.json",
  "type": "log"
}
```
