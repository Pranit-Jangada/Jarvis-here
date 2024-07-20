<html lang="en">
<body>
<script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; 
			embeddedservice_bootstrap.init(
				'00D3O0000006Swf',
				'NorthernHub',
				'https://abb--comfsldev.sandbox.my.site.com/ESWNorthernHub1707191425001',
				{
					scrt2URL: 'https://abb--comfsldev.sandbox.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://abb--comfsldev.sandbox.my.site.com/ESWNorthernHub1707191425001/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>


</body>
</html>
