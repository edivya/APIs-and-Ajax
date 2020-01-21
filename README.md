#  APIs and Ajax

## Overview

When we make a request to a server-side API, we have no control over how long the response will take to resolve. This can create issues for us when dynamically generating HTML in the DOM as our JavaScript may execute before we’ve received the data we need to render elements. The acronym AJAX is short for “asynchronous JavaScript and XML”. AJAX is the integration of several technologies to address the asynchronicity of the client-server request-response pattern. XML, short for “extensible markup language”, is a specification for encoding documents similar to HTML. It was the standard format for data exchange for many years, but has been largely replaced by JSON, though we still refer to this approach as AJAX. The fetch API was recently introduced to simplify use of the XMLHttpRequest object without the need for a third-party library, such as jQuery.
