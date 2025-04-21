# Smart On-Call Scheduling for Global Teams — Now Live on Zenduty

If you're part of a DevOps or SRE team, you know how tricky on-call schedules can get. Add different timezones, holidays, or personal work hours to the mix, and it becomes even more complicated. We’ve been there too, and that’s exactly why we built something better.

Today, we’re excited to launch **Advanced On-Call Scheduling with Timezone Intelligence** on Zenduty.

This new feature makes managing on-call shifts simpler, fairer, and more human. It’s designed for real-world teams where people live in different timezones and have different working hours.

Let’s walk you through what’s new and how it helps.

---

## Why we built this

A lot of on-call systems assume that everyone works 9 to 5 in the same timezone. That doesn’t work anymore. Teams today are global. Some members might start their day in Singapore while others are just ending theirs in California.

We spoke with many SREs and developers. They told us that what matters most is balance. Nobody wants to be woken up at 3 AM just because the system couldn’t figure out who was actually available at that time.

So we asked ourselves, “What would on-call scheduling look like if it respected people’s time?”

That’s how this feature came to life.

---

## What’s new

Here’s what you can now do with Zenduty’s advanced scheduling:

### 1. Timezone-aware schedules  
You can now add each user with their own timezone. The system understands where they are in the world and adjusts the schedule accordingly.

### 2. Custom working hours  
Each participant can also have defined working hours. Someone may prefer 7 AM to 3 PM while someone else works 12 PM to 8 PM. Zenduty will only schedule them during the times they’re available.

### 3. Rotations that fit your team  
You can create daily, weekly, or even custom rotations. Whether you want to rotate shifts every day or every few days, you have full control.

### 4. Holiday calendars  
Add public or regional holiday calendars to your schedule. Zenduty will skip those days automatically. No one gets alerts during their holidays.

### 5. Fallback users  
Sometimes, no one is available. In that case, you can assign a fallback user who will be notified. It’s like a safety net for your alerts.

---

## How it works

You can set up your schedule using our updated API. It’s simple and built with developers in mind. Here are the main things you’ll need:

- **Name your schedule**
- **Set the start date**
- **Choose the rotation type**
- **Add participants with their timezone and working hours**
- **Optional: Add holiday calendars and fallback user**

You can also update, delete, or fetch schedules through the API. All of this is documented and available through our [release note]("./RELEASE_NOTE.md").

We’ve also added a Postman collection to make it easier to try out each endpoint without writing code.

---

## Try it out

If you want to see it in action, here’s a quick way to get started:

1. Import the Postman collection from our GitHub repo  
2. Use the mock server to test creating and listing schedules  
3. Add your timezone, working hours, and test how Zenduty distributes the shifts  

You’ll see how each rotation respects timezones and avoids assigning users outside of their working hours.

---

## What’s next

This is just the beginning. We’re already exploring features like:

- Visual drag-and-drop calendar UI for managing schedules  
- Slack and email summaries of who’s on-call each day  

We’d love your feedback. If you have suggestions or ideas, or if something isn’t working the way you expected, please let us know.

You can also join our community to connect with other developers and SREs using Zenduty: [https://community.zenduty.com](https://community.zenduty.com)

Whether you're running a small dev team or supporting a global operation, we hope this helps you sleep better and work smarter.

Thanks for being a part of the Zenduty community ❤️
