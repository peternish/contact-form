# Got it David???

# contact-form
contact form sample that uses emailjs

# Requirements
No special technical requirements but just make sure that you have the [EmailJS](https://dashboard.emailjs.com/) account.

## user_id 
You can find it in your [emailjs account](https://dashboard.emailjs.com/admin/account) list. It's named as a public key.
## service_id
To use emailjs you have to create a [new service](https://dashboard.emailjs.com/admin).
After adding a new service you can find your service id in your service item.
## template_id
[EmailJs template](https://dashboard.emailjs.com/admin/templates) is kind of a model that defines the data format and exact data items(defined by 'name' in your form).
Here is a sample template which I made for form 1.

Hello {{person's name who will recieve this mail}},

You got a new application message from {{email}} {{firstName}} {{lastName}}:

startDate : {{startDate}}

firstName: {{firstName}}

lastName: {{lastName}}

height: {{height}}

weight: {{weight}}

date of birth: {{dob}}

stateOfBirth: {{stateOfBirth}}

ssn: {{ssn}}

employer: {{employer}}

occupationDuties: {{occupationDuties}}

residentialAddress: {{residentialAddress}}

city: {{city}}

state: {{state}}

zip code: {{zip}}

email: {{email}}

phone: {{phone}}

Best wishes,
Peter.

### all information inside {{}} is the variable you get from form by their 'name' feature.

