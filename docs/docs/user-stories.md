# ServiceFlow User Stories

## US-001: View Services

As a customer, I want to view available services so that I can choose the service I need.

### Acceptance Criteria

- The service list displays the service name, description, price, and duration.
- Only active services are displayed.
- A customer can open a service to view more details.
- A suitable empty-state message appears when no services are available.

## US-002: View Available Slots

As a customer, I want to view available appointment slots so that I can select a convenient time.

### Acceptance Criteria

- Only future slots are displayed.
- Already-booked slots are not available for selection.
- Slots are displayed for the selected service.
- A message appears when no slots are available.

## US-003: Book an Appointment

As a customer, I want to book an available appointment so that the selected service is reserved for me.

### Acceptance Criteria

- The customer must be signed in.
- The customer must select a valid service and available slot.
- The system prevents two customers from booking the same slot.
- A successful booking receives a unique reference number.
- The customer sees a confirmation after booking.

## US-004: View My Bookings

As a customer, I want to view my bookings so that I can track upcoming appointments.

### Acceptance Criteria

- A customer can only see their own bookings.
- Upcoming and previous bookings are clearly identified.
- Each booking displays its service, date, time, and status.

## US-005: Manage Services

As an administrator, I want to manage services so that customers see accurate service information.

### Acceptance Criteria

- Only administrators can access service management.
- An administrator can create and update a service.
- Required information is validated.
- A service can be made inactive without being permanently deleted.