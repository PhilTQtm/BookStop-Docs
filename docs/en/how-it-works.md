# <span translate="no">How It Works</span>

This section takes you through a high level overview of the **BookStop** booking system. 
Understanding its structure will assist greatly when getting started and configuring the 
system to your unique requirements.  

## Two Sites

The system is split across 2 unique URL's. (web addresses) One is used for administration 
and configuration (bookstop.app), the other is the site your customer sees when making a 
booking (bookstop.online).

## Tenants

When you sign up to use the system you are known as a 'Tenant'. A Tenant structure is used to 
group all your information together and is completely independent of other Tenants who may also use 
the system. Your Tenant name becomes part of a unique web address to navigate to your site.  

For example, your company is called 'Arks Arkade', your tenant name could be 'arksarkade', your 
unique web addresses would then be 'arksarcade.bookstop.app' and 'arksarcade.bookstop.online'.

## BookStop.Online

This is the customer facing site, the thing your customers interact with when they want to find 
out about you, your company and to make a booking.  

The site contains several pages by default, a home page, a contact form, a FAQ and a booking 
availability and confirmation page. Page content can be maintained from within BookStop.App 
and customised to your requirements. 
Generally these are all you need for a basic web presence with integrated booking, but the option 
is also available to create additional pages and add them into the top menu for those that need 
more.

## BookStop.App

This is the administration and configuration portal for **BookStop**. Here you manage all things 
seen by customers on BookStop.Online: 

- page content 
- contact information, emails, phone, socials etc
- resources (things that are bookable, i.e. you, staff, rooms etc)
- availability, designated into 'bookable slots'

You also manage all bookings received from your customers:

- resource booked
- time booked
- payments made against the booking
- status of the booking (confirmed, fulfilled) 

## Stripe Integration

For payments at the time of booking, we integrate with **Stripe**. You define a booking policy to suit, 
e.g. take deposit, take full payment etc, then in order to confirm the booking, the appropriate payment 
must be made. 

**Stripe** integration is straightforward. Go to **Stripe** and complete their On-Boarding 
procedure to set up a **Stripe** account, this ensures all statutury money/payment laws are complied 
with in your duristiction.  

Once complete, retrieve your secret API key and link it to BookStop. Bookstop will then use this to 
process online payments. You maintain full control over payment collections and funds.  

If no payment at the time of booking is required, this can be skipped.


