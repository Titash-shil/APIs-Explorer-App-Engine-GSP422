# || APIs Explorer: App Engine [GSP422](https://www.cloudskillsboost.google/games/5703/labs/36449) ||

## # Like, comment, share & Don't forget to subscribe [Qwiklab_Explorers_ts](https://youtube.com/@titashshil?si=RgamNu1dc9jVIbJN) 👍😄🤝

---
## ⚠️ **Disclaimer:**
#### This script and guide are provided for educational purposes to help you understand the lab process. Please ensure you understand the steps before using any scripts. Before using the script, I encourage you to open and review it to understand each step.The goal is to help you learn how to complete the labs effectively while following Qwiklabs' terms of service and YouTube's community guidelines.
---

- ### Copy & Run :

```

echo ""
echo ""

read -p "Enter REGION: " REGION

gcloud auth list

git clone https://github.com/GoogleCloudPlatform/python-docs-samples

cd ~/python-docs-samples/appengine/standard_python3/hello_world

export PROJECT_ID=$DEVSHELL_PROJECT_ID

gcloud app create --project $PROJECT_ID --region=$REGION

echo "Y" | gcloud app deploy app.yaml --project $PROJECT_ID

echo "Y" | gcloud app deploy -v v1
```

---

## Congratulations ..!!🎉  You completed the lab shortly..😃💯

## *Well done..!* 👏

## Thank you for visiting.... :) 🗯️

## [Qwiklab_Explorers_ts](https://youtube.com/@titashshil?si=RgamNu1dc9jVIbJN)

## Join to our community [Digital Dominators](https://chat.whatsapp.com/J0o1beFGCHfJ8ZHGKjcqkd)
