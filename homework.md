_In preparation for 

## 1. Create Tag Manager Account
- [Create a Google Tag Manager Account](https://support.google.com/tagmanager/answer/2574370?hl=en)
- You'll be prompted to "create a tag". Ignore this for now, but save the snippet somewhere convenient. It looks like this:

```<!-- Google Tag Manager [example.gov] -->
<noscript><iframe src="//www.googletagmanager.com/ns.html?id=GTM-5WL4TR"
height="0" width="0" style="display:none;visibility:hidden"></iframe></noscript>
<script>(function(w,d,s,l,i){w[l]=w[l]||[];w[l].push({'gtm.start':
new Date().getTime(),event:'gtm.js'});var f=d.getElementsByTagName(s)[0],
j=d.createElement(s),dl=l!='dataLayer'?'&l='+l:'';j.async=true;j.src=
'//www.googletagmanager.com/gtm.js?id='+i+dl;f.parentNode.insertBefore(j,f);
})(window,document,'script','dataLayer','GTM-5WL4TR');</script>
<!-- End Google Tag Manager -->```

### Instructions:

You will need a Google account; for convenience use the same email used to log in to Google Analytics.
![](https://raw.githubusercontent.com/laurenancona/unified-analytics/master/images/1-signup-screen.png)
- Go to the **[Google Tag Manager](https://tagmanager.google.com)** website. Log in to Google if required.
- Enter **Account Name** (e.g. `Example Government Name`)
- Enter **primary domain** to be measured, e.g. `example.gov`
- Agree to **Google Tag Manager Use Policy**

The snippet of code to embed on every page will be displayed next. You can always retrieve this from the control panel, but copy and save this for later if you wish.
![](https://raw.githubusercontent.com/laurenancona/unified-analytics/master/images/3-snippet.png)

## 2. Google Analytics Setup
- Recommendation: new/clean GA Profile and
	- 3 Views:
		- Example.gov Reporting
		- Example.gov Testing
		- Example.gov No Filters