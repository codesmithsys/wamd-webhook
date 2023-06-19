# wamd-webhook
Webhook is a feature that allows you to receive a callback from our server when a message is incoming to your device. You can use this feature for made a dinamic chatbot or whatever you want.  We will send a POST request to your webhook url with a JSON body. Here is an example of the JSON body we will send:

{
  "message" : "message",
  "from" : "the number of the whatsapp sender",
  "bufferImage" : "base64 image, null if message not contain image",
}

