<html lang="en">
<body>
 <script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US';
			embeddedservice_bootstrap.init(
				'00D9M000000qSBX',
				'PA_Northern_Hub',
				'https://abb--comstage.sandbox.my.site.com/ESWPANorthernHub1708684533261',
				{
					scrt2URL: 'https://abb--comstage.sandbox.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://abb--comstage.sandbox.my.site.com/ESWPANorthernHub1708684533261/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>

</body>
</html>
