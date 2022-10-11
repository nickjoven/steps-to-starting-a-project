# MANAGING PROJECTS LECTURE

### Example: making a ticketmaster competitor

## Step 1: 

Answer Concept-Level Questions

### What is the idea?
Event management software for large venues

### What functionality does the app need?
1. What libraries do we need/can we use?
2. What tables in the database does the application rely on?
3. What functions or methods need to be written? What arguments will these functions accept/pass? (aka what entities do I need)
4. What does the front end (UI) consist of?
 
### What libraries or tools does the app need?
(it helps to have backup libraries for any given functionality)
- Stripe, braintree, square, paypal
- HTML canvas API (for custom stadium UI designs)
- bcrypt
- devise (for authentication/authorization)
- PostgreSQL
- Heroku/Render/AWS/PythonAnywhere/Fly.io/TinyStacks/EngineYard/GCP/Microsoft Azure
- React

## Step 2:

Categorize your technical specifications (tech specs) into 2 main categories: ESSENTIAL and NON-ESSENTIAL

Essential:
- The ability to buy and sell tickets
- User authentication
- Event publishing for hosts
- Seat choosing for ticket purchasing

Non-essential:
- Chat feature
- Reselling
- Promo codes
- Password-protected event pages
- Survey integration

## Step 3:

Categorize ESSENTIAL and NON-ESSENTIAL items into DO KNOW and DON'T KNOW categories

Things you can 100% reproduce (meaning you've done them before) go under DO KNOW. **Timebox these items and assume an additional 50% will be required.**
- User authentication with devise (3h)
- Deployment (90m)


Anything you have not coded FRONT TO BACK falls into DON'T KNOW
- Payment processing
- user seat choice (front end)
- Seat data modeling (back end)

## Step 4:

Isolate and sandbox tasks from DON'T KNOW
- Work on stripe payment processing in a tiny repo that doesn't involve anything else. This is sandboxing.
- Work on seat choice with index.html, main.css, main.js files and nothing else

Auth/valudations should be the last thing you do

## Important:

At least 33% of the things you do will need to be split into their own sub-tasks.

## Step 5:

Start the project management process

Pick a project management tool, list tasks, and manage tasks throughout the lifecycle of the project.





