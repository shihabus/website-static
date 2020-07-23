# website-static

Serves the static assets and mocked API data for the webapps.

`https://raw.githubusercontent.com/Real-Dev-Squad/website-static/main/[path-to-asset]`

## Directory Structure

```
ids
|__ mapping.json
|
members
|__ [member_id]
|   |__ data.json
|   |__ img.png
|
api
|__ [api_id].json
```

### Data format

#### ids

Unique ids provided to the member by Real Dev Squad

```
{
	[rds_id]: "<github_id>",
	...
}
```

#### members

```json
{
	"id": "[rds_id]",
	"first_name": "Ankush",
	"last_name": "Dharkar",
	"yoe": 8,
	"company": "Pesto Tech",
	"designation": "Instructor",
	"img": "URL to profile pic",
	"github_id": "ankushdharkar"
}
```

> Note: Default img.png co-located in the folder
