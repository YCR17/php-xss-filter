# XSS FILTER

# BY YCR17

## Description

Simple data filter on php

(xss, sql inject and html inject

## Example usage

```

<?php

include('filter_xss_ycr17.php');

echo filter_by_ycr17("<script> alert('hai'); </script> | SELECT * FROM or DELETE *");

?>

```

a
## Authors


ex. [@YCR17](https://github.com/YCR17)

