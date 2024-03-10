### DESCRIPTION
#

https://github.com/kentlouisetonino/node-chatgpt/assets/69438999/58aae521-eb39-482b-875c-97decc2c178b

<br />

> - A backend service that integrates Node.js with ChatGPT API.

<br />
<br />



### LOCAL DEVELOPMENT
#
> - Create `.env` file and insert the key value pair below.

```bash
PORT=11000
```

> - Execute the scripts.
```bash
# Highly suggest to use Node.js version >= 18.
yarn install
yarn start
```

> - Use postman to send post request.

```plaintext
[REQUEST]
    Method: POST
    URL: http://localhost:11000/api/openai/chat
    Raw-JSON:
        "apiKey": "{{API_KEY}}",
        "model": "gpt-3.5-turbo",
        "messages": [{"role": "user", "content": "Say this is a test!"}],
        "temperature": 0.7
```

> - Further documentation can be found in OpenAI official [docs](https://platform.openai.com/docs/api-reference/introduction).
