Sonerezh Dark Theme
========

Dark theme for Sonerezh stream music application 

Work with Sonerezh v1.0.0-beta

Install
----------------

- Download and extract the project
- Copy and paste "app" directory in your Sonerezh main directory, replace files
- Enjoy !

Uninstall
----------------

- Open app/View/Layouts/default.ctp
replace this ligne : 
	<?= $this->Html->css(array('bootstrap.min', 'jquery.fs.selecter.min', 'pace', 'notify', 'slider', 'style', 'style-dark'));?>
	to
	<?= $this->Html->css(array('bootstrap.min', 'jquery.fs.selecter.min', 'pace', 'notify', 'slider', 'style'));?>

- Open app/View/Layouts/login.ctp
replace this ligne : 
	<?= $this->Html->css(array('bootstrap.min', 'login', 'login-dark'));?>
	to
	<?= $this->Html->css(array('bootstrap.min', 'login'));?>