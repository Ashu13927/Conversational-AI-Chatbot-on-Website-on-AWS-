# Conversational-AI-Chatbot-on-Website-on-AWS

step 1 : Aws  Amazon Lex >> Create Bot (Blank bot - name) >> IAM permission (create a role W basic – COPPA (NO) – IDLE session timeout (5 min)) >> Next >> English (default 	                  language) >> voice interaction (none :: this is only a text based application) >> done
		// intent means :: what user want to say (slot :: fulfil to intent) like small – big pizza means “ Data type”
	
 Ex::
		hotel booking chatbot
		$intent
		 Book hotel
		sample utterance:
		I want a make hotel reservations book a 33 night stay in Mumbai – book a (night) night stay in (location)
	$$ Slots
		Location
		Prompts : what city will you be staying in ?
		check in date
		promps : what day do you want to check in ?

step 2 : Intent details  name (book hotel) >> sample utterances (add utterances) down side (book a hotel) Add (I want a make ….. reservation) Add

step 3 : confirmation prompts & decline responses >> confirmation prompt

$$ other  if doing wrong Message >>
