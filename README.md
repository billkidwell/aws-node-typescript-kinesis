<!--
title: 'AWS Kinesis Data Streams Standard Example (NodeJS & Typescript)'
description: 'This example demonstrates how to setup a Kinesis Producer/Consumer with Typescript.'
layout: Doc
framework: v1
platform: AWS
language: nodeJS
authorLink: 'https://github.com/billkidwell'
authorName: 'Bill Kidwell'
authorAvatar: 'https://avatars0.githubusercontent.com/u/46457910?s=460&u=7c6d271ea7527f05e6c053cab571d32ffb3dbd38&v=4'
-->
# Simple Kinesis Example

This example demonstrates how to setup a Kinesis producer and consumer to send and receive messages through a Kinesis Data Stream.

## Use Cases
- Decouple message producers from message consumers.
- This is one way to architect for scale and reliability.
- Real-time processing of streaming data

## Setup
- sls deploy

## Usage
- To print out the logs of the Kinesis consumer handler on the terminal
  `sls logs -f receiver -t`

- send a HTTP POST request to the sender lambda with a JSON payload

## Acknowledgements
Adapted from Miguel Frazao's [SQS Standard example](https://github.com/serverless/examples/tree/master/aws-node-typescript-sqs-standard).