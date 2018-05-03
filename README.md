# Google Calendar Event Inserter

## Description

Page used to insert an `event` passed in query parameters to user's primary Google Calendar.

## Usage

Passing an event as a query parameter: `?event=<SERIALIZED-JSON>`.

To serialize an event object, use for instance `encodeURIComponent` and `JSON.stringify`.