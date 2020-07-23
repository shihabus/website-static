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
	"github_id": "ankushdharkar",
	"linkedin_id": "ankushdharkar",
	"twitter_id": "ankushdharkar",
	"instagram_id": "ankushdharkar",
	"site": "<bio-website-here>"
}
```
**Important:** Github, LinkedIn, Twitter are mandatory

> Note: Default img.png co-located in the folder

### Rules for Profile picture:

- Images should be a square
- Size of the image should be greater than 500px X 500px
- The face should be visible and identifiable
- The picture should be decent for the purposes of the group
