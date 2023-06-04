# magento2-admin-theme
Magento 2 extension to apply light theme on admin console | Nadeem Khan

## Features:

1. Extension to change the color scheme in Admin console.
5. Looks like core functionality of Magento.
6. Unencrypted code for easy customization

# Installation Instruction

* Copy the content of the repo to the <b>app/code/Nadeem/AdminTheme/</b> folder
* Run command:
<b>php bin/magento setup:upgrade</b>
* Run Command:
<b>php bin/magento setup:static-content:deploy</b>
* Now Flush Cache: <b>php bin/magento cache:flush</b>

# Contribution

Want to contribute to this extension? The quickest way is to <a href="https://help.github.com/articles/about-pull-requests/">open a pull request</a> on GitHub.

# Screenshots & Support

If you encounter any problems or bugs, please <a href="https://github.com/inadeemkhan/magento2-admin-theme/issues">open an issue</a> on GitHub.

<b>Admin Dashboard</b>

![ScreenShot](https://github.com/inadeemkhan/magento2-images/blob/master/admin_theme/Dashboard.png)

<b>Store Cofiguration</b>

![ScreenShot](https://github.com/inadeemkhan/magento2-images/blob/master/admin_theme/Configuration.png)

<b>Admin products</b>

![ScreenShot](https://github.com/inadeemkhan/magento2-images/blob/master/admin_theme/Product-Page.png)

## Prerequisites

### Use the following table to verify you have the correct prerequisites to install this Extension.
<table>
	<tbody>
		<tr>
			<th>Prerequisite</th>
			<th>How to check</th>
			<th>For more information</th>
		</tr>
	<tr>
		<td>Apache 2.2 or 2.4</td>
		<td>Ubuntu: <code>apache2 -v</code><br>
		CentOS: <code>httpd -v</code></td>
		<td><a href="https://devdocs.magento.com/guides/v2.2/install-gde/prereq/apache.html">Apache</a></td>
	</tr>
	<tr>
		<td>PHP 7.*.*</td>
		<td><code>php -v</code></td>
		<td><a href="http://devdocs.magento.com/guides/v2.2/install-gde/prereq/php-ubuntu.html">PHP Ubuntu</a><br><a href="http://devdocs.magento.com/guides/v2.2/install-gde/prereq/php-centos.html">PHP CentOS</a></td>
	</tr>
	<tr><td>MySQL 5.6.x</td>
	<td><code>mysql -u [root user name] -p</code></td>
	<td><a href="http://devdocs.magento.com/guides/v2.2/install-gde/prereq/mysql.html">MySQL</a></td>
	</tr>
</tbody>
</table>

### Feedback and Support 

<a href="mailto:khannadeem243@gmail.com">khannadeem243@gmail.com</a>
