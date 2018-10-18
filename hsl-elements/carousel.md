## Carousel

#### Sample Json for default Carousel
```json
{
	"text": "Here are the latest scorecards for the Delhi Daredevils vs. Kings XI Punjab match 🔢",
	"type": "CAROUSEL",
	"data": {
		"image_aspect_ratio": 1.69,
		"width": "THIN",
		"items": [{
			"thumbnail": {
				"image": "http://haptikappimg.haptikapi.com/Cricket_Images/Base_Template/Thumbnail_Innings_1.png"
			},
			"title": "DD: 166/7 (20.0 overs)",
			"sub_title": "KXIP: Bowling",
			"description": "",
			"actionables": [{
				"actionable_text": "View Scorecard",
				"location_required": false,
				"is_default": 0,
				"uri": "CAROUSEL_DETAIL",
				"type": "APP_ACTION",
				"payload": {
					"title": "DD vs. KXIP",
					"sub_title": "1st Innings",
					"description": "DD: 166/7 (20.0 overs)",
					"images": ["http://haptikappimg.s3.amazonaws.com/Cricket_Images/Match_Scorecard/Innings_Score_Batting_1_186013_1_1523189431.png", "http://haptikappimg.s3.amazonaws.com/Cricket_Images/Match_Scorecard/Innings_Score_Batting_2_186013_1_1523189432.png", "http://haptikappimg.s3.amazonaws.com/Cricket_Images/Match_Scorecard/Innings_Score_Bowling_186013_1_1523189431.png"],
					"gogo_message": "",
					"link": ""
				},
				"emoji": ""
			}]
		}, {
			"thumbnail": {
				"image": "http://haptikappimg.haptikapi.com/Cricket_Images/Base_Template/Thumbnail_Innings_2.png"
			},
			"title": "KXIP: 167/4 (18.5 overs)",
			"sub_title": "DD: Bowling",
			"description": "",
			"actionables": [{
				"actionable_text": "View Scorecard",
				"location_required": false,
				"is_default": 0,
				"uri": "CAROUSEL_DETAIL",
				"type": "APP_ACTION",
				"payload": {
					"title": "DD vs. KXIP",
					"sub_title": "2nd Innings",
					"description": "KXIP: 167/4 (18.5 overs)",
					"images": ["http://haptikappimg.s3.amazonaws.com/Cricket_Images/Match_Scorecard/Innings_Score_Batting_1_186013_2_1523197798.png", "http://haptikappimg.s3.amazonaws.com/Cricket_Images/Match_Scorecard/Innings_Score_Batting_2_186013_2_1523197799.png", "http://haptikappimg.s3.amazonaws.com/Cricket_Images/Match_Scorecard/Innings_Score_Bowling_186013_2_1523197798.png"],
					"gogo_message": "",
					"link": ""
				},
				"emoji": ""
			}]
		}]
	}
}
```

#### Sample Output
![hsl_sample_carousel](hsl_sample_carousel.png)


#### Sample Json for mini actionable
```json
{
	"text": "Here is a Saving Tip for you",
	"type": "CAROUSEL",
	"data": {
		"image_aspect_ratio": "1.67",
		"width": "FAT",
		"items": [{
			"thumbnail": {
				"image": "http://haptik-staging.s3.amazonaws.com/Image%20Generator/money_saving_tip/money_saving_tip_ad712a04-065d-409a-bcbe-94dfc9e3ef56.png?w=1068&amp;h=639"
			},
			"actionables": [],
			"mini_actionable": {
				"actionable_text": ":share: Share",
				"location_required": false,
				"is_default": 0,
				"type": "SHARE",
				"payload": {
					"show_share_option": true,
					"image": "http://haptik-staging.s3.amazonaws.com/Image%20Generator/money_saving_tip/money_saving_tip_ad712a04-065d-409a-bcbe-94dfc9e3ef56.png?w=1068&amp;h=639",
					"gogo_message": "",
					"message": "A great Saving Tip for you!"
				},
				"uri": ""
			}
		}]
	}
}
```

#### Sample Output
![hsl_mini_actionable_carousel](hsl_mini_actionable_carousel.png)
