# basic-card.css
> css for creating basic cards with only css

## Example
<div style="text-align:center">
<img src="https://i.imgur.com/QkIfHFk.png" alt="styled card preview" width="350px" />
</div>

```html
<!DOCTYPE html>
<html>
<head>
	<title>basic-site-card-test</title>
	<link rel="stylesheet" type="text/css" href="basic-card.css">
	<style type="text/css">
		* {
		  box-sizing: border-box;
		}

		html {
		  font-family: "Helvetica Neue", "Roboto", sans-serif;
		}

		.basic-card {
		  margin: auto;
		  margin-top: 25vh;
		  width: 300px;

		  box-shadow: 0 4px 14px rgba(0, 0, 0, 0.12);
		  border-radius: 10px;
		  border: 3px solid rgba(50, 50, 50, 0.12);
		}

		.basic-card .basic-card-image {
		  overflow: hidden;
		  max-height: 512px;
		}
	</style>
</head>
<body>
	<div class="basic-card" style="--card-color: #1e2327;">
		<div class="basic-card-image">
			<img src="https://github.githubassets.com/images/modules/open_graph/github-octocat.png">
		</div>
		<div class="basic-card-hr"></div>
		<div class="basic-card-header">
			<div class="basic-card-title">Build software better, together</div>
			<div class="basic-card-subtitle">GitHub</div>
		</div>
		<div class="basic-card-content">
			<div class="basic-card-description">GitHub is where people build software. More than 36 million people use GitHub to discover, fork, and contribute to over 100 million projects.</div>
		</div>
	</div>
</body>
</html>
```