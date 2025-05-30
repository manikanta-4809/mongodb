## added 10 entries
<img width="728" alt="image" src="https://github.com/user-attachments/assets/777427cd-36dd-4c79-999f-68534ba08812" />

## making in progress as flase and done as true

<img width="721" alt="image" src="https://github.com/user-attachments/assets/a4663f46-f5f4-46bb-b6e8-fd3779642dae" />
<img width="725" alt="image" src="https://github.com/user-attachments/assets/21088353-a0d5-44d8-884b-da7291dc1d22" />

## making all the entries as false

<img width="721" alt="image" src="https://github.com/user-attachments/assets/03eb7e39-0652-4880-a2c8-8a30f04777fd" />

## inserting one new entry as false

<img width="724" alt="image" src="https://github.com/user-attachments/assets/e76e9a3c-97a1-4682-aad4-af916862fd1a" />

## making new entry as true

<img width="721" alt="image" src="https://github.com/user-attachments/assets/871a94f1-7be9-4c13-b9f5-8bd635e3780b" />

## adding new date as created_at

<img width="721" alt="image" src="https://github.com/user-attachments/assets/b0ae2c95-08d9-4376-9807-590334ac5d60" />

## assigning deadline to all 

<img width="722" alt="image" src="https://github.com/user-attachments/assets/c3d18732-114c-47f6-93f5-6d8ae9f0c756" />

## count of the documents and also count of specific document

<img width="718" alt="image" src="https://github.com/user-attachments/assets/2bd59e3e-1ea4-4703-8445-894b59895829" />

## like updated time before 7 mins

<img width="720" alt="image" src="https://github.com/user-attachments/assets/a5a1a21d-4db6-427e-84ce-43d8610be239" />


### Explanation

I created a database in MongoDB Compass, assigned a database name, and created a collection. I then inserted 10 documents into the collection. For all 10 documents, I set the inprogress field to false and the done field to true. Next, I added a new document (the 11th entry) with the inprogress field set to false by default. Using the newly created document’s _id, I updated its inprogress field to true. After that, I added new_date and created_at fields to all 11 documents. I then retrieved all documents using the find command. Additionally, I set a deadline field for all 11 documents. I used the countDocuments command to count the total number of documents in the collection. Finally, I queried for documents where the done field was updated within the last 7 minutes and retrieved the timestamp for a specific document.
