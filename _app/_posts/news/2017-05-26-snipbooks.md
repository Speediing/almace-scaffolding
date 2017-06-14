---
heading-img: https://s3-us-west-1.amazonaws.com/www.jasonwiker.ca/assets/img/snipbooksLogoWhite.png
heading-img-local: true
heading-bg-color: "#8141b1"
heading-bg-text: "#fff"
layout: post
title: "Snipbooks"
category: projects
tags: projects
comments: true
---

![alt-text](https://s3-us-west-1.amazonaws.com/www.jasonwiker.ca/assets/img/ipad1.jpg){: .size-left} 

Snipbooks is an iOS based salon management app that aims to simplify the workflow of salon employees and customers. The goal was to make an app that replaces the paper schedule system that salons were currently using. We have worked with people in the salon industry to find the most optimal way of doing this and we came up with a multi interface design. The primary one being for the receptionist’s IPad at the front of the Salon who can view and book appointments for all stylists and see all the customer details for the salon. Then there is a view for the Stylist’s themselves that includes a calendar for the given day, a way to approve and deny new appointments and a way to update logistical details like the hours they work. The last view is the customer facing one that allows them to view salons, stylists and create appointments.

A big reason that salons had not adopted booking systems in the past is that a lot of stylists have the capability to take in multiple customers at the same time and the systems before didn’t have the flexibility for this. An example of this being that if a customer wants a coloring and a haircut there will be break in between as the color sets in the hair. The stylist then has time to take other customers and the prior booking systems didn’t have this ability. We made this a priority and our calendar system was created around it. When a customer books an appointment, they can also book follow up appointments and this is shown in the calendar with two appointments that have a lighter block in-between them.

![alt-text](https://s3-us-west-1.amazonaws.com/www.jasonwiker.ca/assets/img/ipadcal.jpg){: .size-small} 

The Receptionist View was where we made a lot of components then reused them elsewhere in different parts of the app. It is also the most complicated part as it has many different nested components and moving parts, the biggest of which being the calendar. This view is at the front of the salon on an IPad for the receptionist. On the main screen, you can see all the stylists at the top with their schedules underneath them. The receptionist can scroll through and tap on appointments to bring up more details about the booking. If the customer needs to change the time of the appointment the receptionist can adjust that, as well as the services being done. They can also call the customer directly from there. In addition to the calendar the receptionist can also see the booking requests for all the stylists and approve or deny them. They again have all the control to change the appointment details if necessary. Finally, they have access to the records of all the customer details and can view/update them as necessary.

![alt-text](https://s3-us-west-1.amazonaws.com/www.jasonwiker.ca/assets/img/snipbooksCal.jpeg){: .size-right} 

The Stylist portion builds off the Receptionist but presents it in a more compact phone view and adds more stylist specific options. It has the same calendar components that the receptionist has except it only shows the currently signed in user. It also has a different UI for moving around days including swiping across the view or using the buttons on the top to jump to a specific date. You can also tap on the date at the top to bring up a date picker to choose a date far in the past or future. Inside the calendar, you can tap on the booking to get more specific details. You also have the same options to update the booking as necessary. The Stylist also can view their appointment requests just like the receptionist except it only shows their own requests. They also have the option to update their stylist profile with their Instagram name, description or other personal details they would like to show to customers. A Stylist also has the power to update logistical work details such as the time they can work and book time off.
![alt-text](https://s3-us-west-1.amazonaws.com/www.jasonwiker.ca/assets/img/stylist3.jpg){: .size-small}


![alt-text](https://s3-us-west-1.amazonaws.com/www.jasonwiker.ca/assets/img/customer.jpg){: .size-right} 
The Customer view is what someone who isn’t affiliated with a salon is shown. The first thing is a list of salons currently using Snipbooks and a customer can tap on it to bring up more details such as a description, phone number, address and the list of stylists. A customer can view the individual profiles of the stylists to see if they want to book with them or not. The profile also features the stylist’s Instagram if they want, because a lot of stylists use it as a marketing tool to show off their work. When a customer is happy with their choice of salon and stylist they can move to the booking wizard to set an appointment with exactly what they want. In the wizard, they are prompted to pick a time and which services they want. They can also attach notes and a picture to allow the stylist to prepare for them beforehand. All of this being as seamless and easy for the user as possible.

![alt-text](https://s3-us-west-1.amazonaws.com/www.jasonwiker.ca/assets/img/stylist1.jpg){: .size-left} 
Our entire app uses a style guide that we created to allow for a clean and consistent user interface throughout. Our color use and font style and size was all chosen to keep a modern looking UI and a point of reference we looked at was the Apple Music App. We really liked how the app looked and thought it was a good jumping point that we could build our interface off of.

We are currently finishing the app and starting development of a web interface as well. The web interface being critical to get any traction for our service. There is no timeline currently for a launch because of busy schedules but we hope to get the process going as soon as possible. Also the code is currently not open source because we are planning on commercializing Snipbooks but I am open to answering any questions you may have about the project in general.

![alt-text](https://s3-us-west-1.amazonaws.com/www.jasonwiker.ca/assets/img/finalsnip.jpg){: .size-small} 
