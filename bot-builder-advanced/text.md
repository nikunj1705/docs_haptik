## HSL Text Element

#### Sample Json
```json
{
	"text": "Hi ! There, this is a quick text message with some quick replies.",
	"type": "TEXT",
	"data": {
		"quick_replies": [{
			"actionable_text": "Show another quote",
			"is_default": 0,
			"type": "TEXT_ONLY",
			"payload": {
				"link": "",
				"message": "Show another quote{task}",
				"gogo_message": "",
				"test4": "4"
			},
			"test3": "3"
		}, {
			"actionable_text": "Thanks",
			"is_default": 0,
			"type": "TEXT_ONLY",
			"payload": {
				"link": "",
				"message": "Thanks",
				"gogo_message": ""
			}
		}, {
			"actionable_text": "❌ Stop updates",
			"is_default": 0,
			"type": "TEXT_ONLY",
			"payload": {
				"link": "",
				"message": "❌ Stop updates{reminder_list: 170, user_id: 202308, task_name: Motivational Quote, offset: 0, api_name: exotel }{task}",
				"gogo_message": ""
			}
		}],
		"test1": "2"
	},
	"test1": "1"
}
```

#### Sample Output
![hsl_sample_text](hsl_sample_text.png)