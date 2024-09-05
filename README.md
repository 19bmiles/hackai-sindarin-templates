# Sindarin AI Templates

This repository contains a collection of templates for creating AI personas using the Sindarin platform. These templates are designed to showcase different capabilities and use cases for voice-based AI interactions.

## Setting Up a Template

To set up any of the templates in this repository on the Sindarin platform, follow these general steps:

1. Navigate to the Sindarin platform and create a new persona.
2. Click on the persona and in its settings, go to the "General" page:
   - Copy the content from the `initial_message.txt` file and paste it into the "Initial Message" field.
   - Copy the content from the `prompt.txt` file and paste it into the "Prompt" field.
3. On the "Actions" page:
   - Copy the content from the `actions.json` file and paste it into the JSON field on the right side of the page.

## Deploying your AI persona
1. Click on the deploy button in the top right corner
2. Click on the Twilio option and follow the steps 
   - Don't forget to add your number as a "Verified Caller ID", so you can try calling the number in trial mode

## Available Templates

### Empathic Listener

**Description**: This template creates an AI therapist persona that focuses on active listening and encouraging users to express their feelings and experiences. It includes a special action to allow for moments of silence, giving users space to continue speaking without interruption.

**Use Case**: Ideal for creating a supportive conversational environment or for practicing empathetic communication skills.

### Appointment Scheduler

**Description**: This template sets up an AI assistant capable of managing appointment bookings. It handles tasks such as collecting user information, checking calendar availability, and confirming appointments.

**Use Case**: Useful for businesses or services that require efficient scheduling and management of appointments.

### Mission Control

**Description**: This template simulates a mission control operator guiding a user through a multi-stage rocket launch procedure. It demonstrates how to chain multiple actions together to create a complex, sequential interaction.

**Use Case**: Great for educational purposes, showcasing how AI can guide users through complex procedures, or for creating interactive storytelling experiences.