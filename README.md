# GCP Google App Engine Demo

This repository is for GCP demo, on Qlue X Digitaraya X CloudAce Webinar, 22 April 2020.

## Getting Started

These instructions will tell you about how easy it is to deploy to the Google App Engine in Google Cloud Platform.

### Prerequisites

What things you need?

- A google account that has been registered in GCP.
- Project with billing enabled on GCP.
- Google Cloud SDK installed.
- Installed NodeJS for local testing.
- Postman App for testing the API.


### Installing Google Cloud SDK

Go to this page for updated installation process.

[Installing Google Cloud SDK](https://cloud.google.com/sdk/install) - from Google Cloud.

## How to use this repo

The master branch is the final product of this demo, to find out step by step, you can navigate using existing tags.

```
git checkout TAG_NAME
```
for running on local environment.

```
npm start
```

## Deployment

After the code is running well on your local environment, hit this on your shell.

```
gcloud config set project YOUR_PROJECT_ID
gcloud app deploy
```

## Built With

* [Express](https://expressjs.com/) - The web framework used
