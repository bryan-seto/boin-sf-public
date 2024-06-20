# Boinboin (alpha)

## Setting up

### Prerequisites

- IDE of your choice (VS Code, JetBrains)
- An API key from us (click [here](https://wa.me/6581125657?text=Hello%20Bryan!%20I%27m%20XX%20and%20I%20got%20to%20know%20about%20your%20apex%20AI%20dev%20tool%20from%20XX.%20Can%20I%20have%20an%20API%20key%20generated%20for%20me%20please) to request for a key!)

### 1. Setting up Continue extension

> - Download [**Continue**](https://www.continue.dev/) from the IDE's marketplace
> - Follow the video recording below to set up your Continue to work with Boin

```
{
  "title": "Boinboin Prod",
  "provider": "openai",
  "model": "",
  "apiBase": "https://boin-sf-nexus-lt7znyigfq-uc.a.run.app/openai/v1",
  "requestOptions": {
    "headers": {
      "x-api-key": "00000000-0000-0000-0000-000000000000" // Replace with your own API key
    }
  }
}
```

https://github.com/samsonong/boin-sf-public/assets/5508315/cd0a62cb-17cd-4193-ad3f-e54f400caf9f

### 2. Basic chat/question

>  Select "Boinboin Prod" as your model, and ask away!
>  If "Boinboin Prod" doesn't show up, restart your IDE

https://github.com/samsonong/boin-sf-public/assets/5508315/0f18a160-a2c6-4e2d-bce6-a36870a0a08c

### 3. Adding a chunk of code as context to your question

> Highlight and press <kbd>CMD</kbd>+<kbd>L</kbd> (<kbd>CTRL</kbd>+<kbd>L</kbd> for Windows)

https://github.com/samsonong/boin-sf-public/assets/5508315/7a6a69bb-a3db-4343-8aec-b9a5669261fb

### 4. Adding a file as context to your question

> Typing @files will bring up a searchable list of files in your repo

https://github.com/samsonong/boin-sf-public/assets/5508315/8a83f9ca-1232-46df-9dee-a0cecc55d2c6
