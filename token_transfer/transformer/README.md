# Transformer

This package provides an example implementation of the transformer layer for Chain Indexer Framework. This layer consumes events from the Kafka topic produced by the Producer and performs filtering based on MATIC token transfers. It then re-produces the filtered events to specific Kafka topics corresponding to each event.

## How to Use

Note: Make sure you are inside the example/matic_transfer/transformer folder.

### 1. Set Configuration

Begin by configuring your environment variables. Copy the `.env.example` file and rename it to `.env`. Then, provide appropriate values for the keys mentioned in the `.env` file.

### 2. Install Packages

Install the required packages by running the following command:

```
npm i
```

### 3. Build the Package

Build the package by executing the following command:

```
npm run build
```

### 4. Run the Package

Run the producer service using the following command:

```
npm run start
```

This documentation clarifies the setup and usage of the Transformer package in the Chain Indexer Framework project, making it easier for developers to integrate the package into their applications or utilize it for debugging and testing purposes.
