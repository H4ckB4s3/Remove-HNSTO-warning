# HNS.TO Warning Removal Script

This repository demonstrates a simple HTML page displaying "Hello World" with accompanying CSS to remove specific elements.

## Usage

Add this in the header:
```  
<style>
  a[href="https://www.hns.to"],
  div[style*="background-color: rgb(241, 0, 19);"],
  div[style="margin: 0; padding: 0; height: 75px"] {
    display: none !important;
  }
</style>
```

## License

No license, no limits. Free to use, abuse and improve this code however you see fit.
