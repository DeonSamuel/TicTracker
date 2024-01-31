# TicTrack
## Ticket Tracking application using MERN stack 

# Ticketing System:
## Scope:
The scope of this system is to track and record customer complaints.

# Users:
1. Reporter (customer-facing care)
2. Assignee (anyone who investigates the problem)


# Use Cases:
1. Reporter should be able to create a ticket with details like :
   1. Title (free-flowing text, req)
   2. Desc (free-flowing text, optional)
   3. Reason (dropdown, req)
	
2. Assignee can assigne the ticket to himself 

3. Every ticket will have a status associated with it
   1. Ticket will be opened in 'OPEN' status
   2. When the assignee assigns himself, the ticket goes to 'IN_PROGRESS'
   3. When the issue is resolved, the ticket will go to 'CLOSE' status

4. The reporter should be able to close the ticket

# Future enhancements:
1. Status can come from DB instead of hard coding
2. feature for adding comments 
3. feature for adding attachments (pdf, image)
4. Technical enhancements (try to merge logic of create and update page)

## Steps:
1. UI mock-up (how is your UI going to look)
	1. List of all tickets
	2. ticket details (create + update)
2. Deciding on tech stack
3. DB Schema
4. Endpoint contract 
5. Implementation
