# Instructions for handling content for Help Centre

This is a change in the readme file made from my desktop


Common rules


Always add <style> at the top to override the styling that Help Centre uses.


```xml
<style> 
h1 { font-size:24px; } 
h2 { font-size:22px; } 
h3 { font-size:20px; } 
h4 { font-size:18px; } 
h5 { font-size:16px; }  
table th { font-size:14px !important; text-align:left !important; }
table td { font-size:14px !important; text-align:left !important; }
</style>
```

!important indicates to Help Centre to override their own style if they have styling set for the same element
