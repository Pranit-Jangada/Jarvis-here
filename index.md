<html>
	<head><meta name="viewport" content="width=device-width, initial-scale=1, minimum-scale=1"></head>
  <body>
    <p>you should be able to chat with person in ComfslDev Salesforce from here</p>
    <script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US';
			embeddedservice_bootstrap.init(
				'00DIS000000J2Dt',
				'jarvis',
				'https://pranit4-dev-ed.develop.my.site.com/ESWjarvis1707642992480',
				{
					scrt2URL: 'https://pranit4-dev-ed.develop.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://pranit4-dev-ed.develop.my.site.com/ESWjarvis1707642992480/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>

  </body>
</html>
