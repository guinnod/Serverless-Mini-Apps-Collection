# Serverless Mini-Apps Collection

## Introduction

This repository is a curated collection of mini-apps designed to operate as serverless cloud functions. As a freelance developer building various MVPs _ranging from admin panels and CRM systems to interactive forms_ I frequently reused certain pieces of code across projects. This collection emerged from the realization that many of these reusable templates could be streamlined into standalone services, thus eliminating the need for repeated copying and pasting.

These mini-apps are primarily designed as HTTP-triggered serverless functions, making them ideal for integration into a variety of projects without the complexities of traditional server management. The use of cloud functions, such as Google Cloud Functions, simplifies deployment and service connectivity thanks to their native HTTP trigger support.

## Project Philosophy

The goal is to provide a suite of simple, easily deployable tools that handle common tasks for freelance projects and beyond. Each function in this repository adheres to the following criteria:
- **Serverless:** Designed to run without the need for a dedicated server.
- **HTTP-triggered:** Can be invoked via simple HTTP requests.
- **Single-purpose:** Each function solves one specific problem.

## Using the Mini-Apps

To use any of the mini-apps in this repository, refer to the specific README.md file in the app's directory for detailed instructions on deployment and usage.

## Current Mini-Apps

1. **Simple Image Compressor API**
   - **Description:** Compresses an uploaded image to a specified maximum size.
   - [More Details](https://github.com/guinnod/image-compresser-api)

2. **Google Storage Photo Uploader**
   - **Description:** Uploads a photo to a specified Google Cloud Storage bucket.
   - [More Details](https://github.com/guinnod/google-storage-uploader/)

3. **Email Sender with File Attachments**
   - **Description:** Sends an email with file attachments.
   - [More Details](https://github.com/guinnod/send-email-with-file/)

4. **CORS Proxy Server**
   - **Description:** Avoid CORS issues when accessing resources from different domains in development.
   - [More Details](https://github.com/guinnod/cors-proxy)

## Contributing

Contributions are welcome! If you're interested in adding a new function or improving existing ones, please ensure your submissions meet the following criteria:
- They must be serverless.
- They must be triggered via HTTP.
- They must solve one specific problem.
