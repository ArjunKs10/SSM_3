# Social Skills Practice App

This project is an interactive iPad app designed to help children practice everyday social communication skills through simple scenarios and guided feedback.

The app presents situations a child might encounter in real life, such as greeting someone, joining a group activity, or speaking politely to a shopkeeper. The goal is to create a safe space where children can practice responses and receive immediate feedback.

## Features

Tap Answers Mode
Children are shown a situation and multiple possible responses. They select the best option and receive feedback explaining why the answer is correct or incorrect.

Speak & Practice Mode
Children respond verbally to social situations using the microphone. The app converts speech to text using Apple's Speech framework and evaluates the response.

Immediate Feedback
A friendly lion character provides guidance and encouragement after each answer to help reinforce good communication habits.

Progressive Scenarios
Multiple real-life situations are included to help children practice different types of social interactions.

Offline Functionality
All speech recognition and logic run directly on the device using Apple's native frameworks, allowing the app to function without an internet connection.

## Technologies Used

Swift
SwiftUI
Speech Framework
AVFoundation
NaturalLanguage (planned for semantic response validation)

## How It Works

In Tap Answers mode, the app compares the selected answer against the correct option defined in the scenario bank.

In Speak & Practice mode, the app listens to the user's speech, converts it into text, and checks the response against expected keywords and phrases related to the scenario.

Future improvements will include using Apple's NaturalLanguage framework to evaluate responses based on meaning rather than simple keyword matching.

## Future Improvements

Semantic response validation using NaturalLanguage embeddings
More real-world social scenarios
Adaptive difficulty levels
Better feedback based on how close a response is to the expected answer
Progress tracking for repeated practice

## Purpose

The goal of this project is to create an engaging and accessible way for children to practice social communication in a structured but low-pressure environment.

Many children benefit from practicing social interactions before encountering them in real life. This app aims to support that process in an interactive and encouraging way.
