![Deep Chat](../../assets/readme/golang-connect.png)

This is an example GO server template that can be used to communicate with the [Deep Chat](https://www.npmjs.com/package/deep-chat) component. It includes a variety of endpoints that can be used to create your own service or act as a proxy for the following AI APIs - [OpenAI](https://openai.com/blog/openai-api), [HuggingFace](https://learn.microsoft.com/en-gb/azure/cognitive-services/), [Cohere](https://docs.cohere.com/docs).

### :calling: UI component

This project is preconfigured to work with the example [UI project](https://github.com/OvidijusParsiunas/deep-chat/tree/main/example-servers/ui). Once both are running - they should be able to communicate with each other right out of the box.

### :computer: Local setup

If you are downloading the project via `git clone` - we advise you to use shallow cloning with the use of the [--depth 1](https://www.perforce.com/blog/vcs/git-beyond-basics-using-shallow-clones) option to reduce its size:

```
git clone --depth 1 https://github.com/OvidijusParsiunas/deep-chat.git
```

Navigate to this directory and run the following command to retrieve the relevant packages:

```
go get
```

Start the server:

```
go run main.go
```

If you want to use the OpenAI API examples, please create an `.env` file and define the `OPENAI_API_KEY` environment variable. See the `.env.example` file.

### :wrench: Improvements

If you are experiencing issues with this project or have suggestions on how to improve it, do not hesitate to create a new ticket in [Github issues](https://github.com/OvidijusParsiunas/deep-chat/issues) and we will look into it as soon as possible.