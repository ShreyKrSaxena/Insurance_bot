## story_00914561
* greet
 - utter_ask_howcanhelp
* inform{"task": "jira"}
 - utter_on_it
 - utter_ask_number
* inform{"number": 12345}
 - utter_ask_status
* inform{"status": "open"}
* deny
 - utter_confirm_number
 - action_suggest
* affirm
 - utter_ack_makereservation
* thankyou
 - utter_goodbye