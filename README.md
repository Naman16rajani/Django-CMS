# Django-CMS: A Simple UI for AWS S3

## Overview

**Django-CMS**, a project that simplifies navigating and managing AWS S3 storage by building an intuitive UI. Say goodbye to complicated AWS navigation and storage limitations on traditional platforms. Using **Python**, **Django**, **JavaScript**, **HTMX**, and other tools, this project aims to provide a user-friendly interface to manage content stored in S3.

## Key Features
- **Simplified AWS S3 Management**: Easily upload, download, and manage files without navigating AWS's UI.
- **Django Backend**: A robust backend for handling S3 operations.
- **HTMX for Interactions**: Lightweight and dynamic frontend interactions.
- **Private Sharing with Twingate**: Securely share your content engine with selected users.
- **Kubernetes Deployment**: Reliable, scalable, and cost-effective app deployment.
- **Auto-Generated Containers with Buildpacks**: No Docker expertise required.
- **Responsive Design**: Built with TailwindCSS and Flowbite for a modern UI.

## Technologies Used
- **AWS S3**: Near-unlimited storage with Python Boto3 SDK for integration.
- **Django**: Backend framework for building the app.
- **HTMX**: Enhances interactivity without overloading JavaScript.
- **TailwindCSS & Flowbite**: For clean and responsive frontend designs.
- **Kubernetes**: Container orchestration for deployment.
- **Buildpacks by Google**: Simplify container creation without Dockerfiles.
- **Twingate**: Securely share private Kubernetes services.

## Usage

1. **Upload Files**: Use the UI to upload large files directly to your S3 bucket.
2. **View & Manage Content**: Browse, download, and organize files.
3. **Secure Sharing**: Use Twingate to allow specific users to access the app.
4. **Monitor Deployments**: Easily scale and manage your app with Kubernetes.

## Project Architecture

- **Frontend**: Built with TailwindCSS and HTMX for dynamic UI/UX.
- **Backend**: Django handles S3 interactions using the Boto3 SDK.
- **Deployment**: Kubernetes with buildpacks ensures scalability and simplicity.
- **Security**: Twingate ensures secure sharing of private resources.
