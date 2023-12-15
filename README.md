# Welcome to Gemini_Model_Test!

- Run below commands for run this project
  - `git clone https://github.com/Yashsoni23/Gemini_Model_Test.git`
  - `cd Gemini_Model_Test`
  - `npm install `
  - now make`.env` file and below variables. Generate API_KEY from [GoogleAI Studio](https://makersuite.google.com/app/apikey)
    ```python
    	API_KEY=[YOUR_API_KEY]
    	PORT=5000
    ```
  - After making .env file hit `npm start` command in terminal.

# Routes

-- **[ `"/"` ]** => { chatbot: "ChatSpot Backend result!!!!"}
-- **[ `"/generate-content-from-image"` ]** => {
text: "{accordingly given images and prompt}" }

- `requestBody =>

```json
    {
    	 prompt : ""
    	 images : [
		    		 {
    			 		base64 : "",
    			 		mimeType : "image/png",
			    	 },{
			    		  add more images same as above object type
		    		 }
    	 		]
    }
```

> Suggestions are accepted => `yashsoni48678@gmail.com`
> Thank you,
