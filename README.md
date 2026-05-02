# AI IT Support Troubleshooting Assistant

## Overview

This is a small project I built to reflect how IT support actually works when users don’t explain their issues clearly.

Instead of jumping straight into fixing things, the focus here is understanding the problem first, then narrowing it down before taking action.

---

## Background

While working in an IT support role, I kept running into the same situation.

A user says something like:
“My email is not working”

At first glance, it sounds simple. But it rarely is.

Sometimes it’s a login issue. Sometimes it’s Outlook. Sometimes it’s network-related. Sometimes it’s just user error.

I realised the real challenge wasn’t fixing the issue — it was figuring out what the user actually meant.

So I built this to reflect and improve that part of my workflow.

---

## What the assistant does

Given a vague issue, the assistant helps to:

* Ask the right questions
* Break the issue into parts
* Suggest possible causes
* Point to the next step

It doesn’t try to be clever. It just follows a clear way of thinking.

---

## How I approach troubleshooting

The logic is based on how I’d handle a real support ticket:

* Don’t assume
* Ask first
* Narrow things down
* Then act

It uses structured prompts to keep that flow consistent.

---

## Example scenario

**User input:**
“My email is not working”

**What happens:**

* It asks what exactly is failing (send, receive, login)
* Checks where the issue is happening (Outlook, browser, phone)
* Suggests likely causes
* Gives simple next steps

## Sample Output

See `outputs/ticket_examples.md` for real examples of how the assistant responds to user issues.

---

## What I took away

This project changed how I approach problems.

Before, I would jump into solutions too quickly.

Now I focus more on:

* Understanding first
* Asking better questions
* Avoiding assumptions

It made troubleshooting feel less random.

---

## What I’d do next

There’s still a lot to build on:

* Add more real scenarios (VPN, printers, lockouts)
* Make the questioning less generic
* Improve how it narrows down issues

---

## Why this approach matters

In real IT support, time gets wasted when the issue isn’t clear.

This kind of approach helps reduce back-and-forth and makes troubleshooting more direct.

