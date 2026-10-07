# Tax Calculator

Container-ready Tax Calculator for the Coursera DevOps final project.

## Local
npm install
npm test
npm start

Open http://localhost:3000

## Docker
docker build -t tax-calculator:1.0 .
docker run --rm -p 3000:3000 tax-calculator:1.0

## Important
The tax brackets are illustrative for this software assignment. Verify real tax rules with an official source before using the calculator for financial decisions.

IBM Cloud registry credentials, deployment URLs, screenshots, and Tekton execution results must be generated from your own IBM Cloud/course environment.
