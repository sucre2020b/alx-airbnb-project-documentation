5 core user stories derived from the use case diagram, formatted with clear role-goal-reason structure:

1. User Registration
   As a guest,
   I want to register an account with email and password,
   So that I can book properties and manage my reservations.

Acceptance Criteria:

Email validation with confirmation link

Password strength enforcement (min 8 chars, special characters)

Unique email constraint

2. Property Listing Creation
   As a host,
   I want to create a property listing with photos, description, and pricing,
   So that travelers can discover and book my property.

Acceptance Criteria:

Multi-image upload (max 10 photos)

Required fields: title, location, amenities, nightly rate

Preview mode before publishing

3. Property Booking
   As a registered user,
   I want to book a property for specific dates,
   So that I can secure my vacation accommodation.

Acceptance Criteria:

Real-time availability calendar

Booking confirmation with total cost breakdown

Instant email/SMS confirmation

4. Payment Processing
   As a user,
   I want to securely pay for my booking via credit card/PayPal,
   So that my reservation is confirmed immediately.

Acceptance Criteria:

PCI-compliant payment gateway integration

Receipt generation with booking details

Failed payment retry mechanism

5. Booking Cancellation
   As a user,
   I want to cancel my booking according to the host's policy,
   So that I can receive a partial/full refund if eligible.

Acceptance Criteria:

Clear display of cancellation policy before booking

Automated refund calculation based on cancellation time

Notification to host about cancellation
