# Twitch-Webhook-To-Discord-Cloudflare-worker
Twitch Webhook -> Cloudflare worker -> Discord Webhook

This project uses a Cloudflare worker to send notifications from a Twitch webhook to a Discord webhook. When a new stream goes live, the worker will receive a request from the Twitch webhook and forward a notification to the Discord webhook. The notification will then appear in the designated Discord channel.

## Getting Started

These instructions will help you set up and deploy the Cloudflare worker for this project.

### Prerequisites

- A Discord account and a Discord webhook set up for the channel where you want to receive notifications
- A Twitch account and a Twitch webhook set up for the events you want to receive notifications for
- A Cloudflare account
