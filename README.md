# JudApp Design

MINIJUST

Poor judgment refers to the inability to make appropriate decisions. If your relative has Alzheimer's or another type of dementia, she might be unable to evaluate the different factors that should be considered when making a decision

causes of poor judgment

    • lack of enough understanding of laws
    • lack of prosecutors at time
    • change of minds of witness
    • lack of facts due to court analysis
    • reporting problems to higher court


Effects of poor judgment


    • Destroys the trust of public sector to act in our best interests
    • Wastes our taxes or rates that have been earmarked for important community projects
    • poor quality services or infrastructure

 SOLUTION 

The only one  solution for these problems is   JudApp , JudApp is the web app that will help the attorney to interact with their client .
It will be the chat application which will help the attorney and client to share the information about the judgment ,  it will contain the article laws of Rwanda .

SERVICES PROVIDED BY JUDAPP

→ laws and its articles
→ witness fact and proofs storage
→  storage folders and other
→ reporting the problem to higher court by attorney
→ simple authentication for the clients

STEPS OF JUDAPP

→ Sign up credentials for the cabinet of attorneys 
→ Sign up credentials for the client
→ authentication of client after it will lock him to near by attorney cabinet by sector or district
→ First he will get all credentials of the group of attorney
→ The attorneys will get the notification for the new client coming
→ The client dashboard will contain general  room for a client and the cabinet of attorney
→ The attorney dashboard will contain general room for all attorney and the clients , the one side bar of clients and the one with all cabinet
→ After finishing all the client should be deleted from the dashboard in the content of all cabinet of the attorney

ALL REQUIRED CREDENTIALS

CABINET CREDENTIALS
→ name of cabinet
→ number of attorneys
→ head of cabinet
→ location {
	province ,district ,sector
	}
Tasks : 
	→ Creating new cabinet
	→ updating the cabinet
	→ getting all cabinets
	→ delete any cabinet

ATTORNEY CREDENTIALS
 → full name
→ email
→ Attorney’s photo
→ phone number
→ cabinet id
→ password for login
Tasks : 
→ Creating the attorney
→ getting the attorney in the same cabinet
→ updating the attorney credential and adding new credentials
→ Deleting the attorney and removing him in the cabinet
→ changing the cabinet of the attorney


CLIENT CREDENTIALS

→ Full name 
→ Location of the client { sector , district , province }
→ password
→ client’s photo
→ workspace id
→ phone number
Tasks :
→ Creating new client 
→ Creating the workspace of new client
→ Getting the attorney with in the same workspace
→ Updating the client’s credentials

WORKSPACE CREDENTIALS 

→ workspace Id
→ client Id if available
→ cabinet Id if available
→ finished Task
Tasks :
→ creating the workspace depending on the users signup
→ getting all work spaces 
→ deleting the workspace
→ workspace themes 

MESSAGE CREDENTIALS

→ message id 
→ workspace id
→ senders id
→ receivers id
→ message content
→ recorded at
→ seen
→ updated : Boolean
Tasks :  
→ recording new message sent 
→ updating the messages
→ deleting the messages
→ getting message by workspace Id
→ getting messages by seen Boolean
→ getting message by updated Boolean

LAW FIRMS SERVICES CREDENTIALS

→ name of service
→ cabinetId
→ type of services (representing , advising , consultation, mediation , arbitration , preparation of document)
→ description
→ attorneyId
Tasks : 
→ adding new service by head of cabinets
→ getting the cabinet based on service type
→ updating the services
→ deleting the services
→ getting the services in the same cabinets

