# panel-collapse
- Collapsable Bootstrap Panels 

## install

- `npm install thismodule`
- import to your code and follow the html pattern.

## css
```
.clickable{
    cursor: pointer;   
}

.panel-heading span {
	margin-top: -20px;
	font-size: 15px;
}
```

## js 

```
import '@nilsonmorais/panel-collapse';

```

## html 
```
<div class="panel panel-default">
	<div class="panel-heading">
		<h3 class="panel-title">My Panel</h3>
		<span class="pull-right clickable"><i class="glyphicon glyphicon-chevron-up"></i></span>
	</div>
	<div class="panel-body">
	</div>
</div>
```