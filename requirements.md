

# Requirements

## Glossaries
* **Admin**: A person who can manage everything on the system.
* **Unregistered User**: A person who is anonymously viewing and searching posts, but can't do any editing.
* **Registered User**: A person who has an account, can share posts and can see others' profiles.
* **Username**: A specific handle that is unique for each registered user.
* **Password**: A specific sequence of characters that will allow registered users to access to the system.
* **Post**: A post that may contain photos, videos, times, audios and quotes.
* **Quote**: Text explanation of the post.
* **Event**: 
* **Profile Page**: 
* **Tags**: 

## 1.Functional Requirements
	
### 1.1. User Requirements

* **1.1.1. Unregistered Users**
   * **1.1.1.1. Register**
      * **1.1.1.1.1.** Unregistered users shall be able to register to the system.
      * **1.1.1.1.2.** Registration form contains mandatory fields which are username, password and e-mail address.
      * **1.1.1.1.3.** Unregistered Users shall be able to use authenticate with their Facebook accounts while registering.
   * **1.1.1.2.** Unregistered Users shall be able to search, browse for posts, registered users and events.
   * **1.1.1.3.** Unregistered Users should not be able to create new posts and events.
   * **1.1.1.4.** Unregistered Users should not be able to like or comment posts and events.
   * **1.1.1.5.** Unregistered Users should not be able to visit any profile page.

* **1.1.2. Registered Users**
   * **1.1.2.1.** Registered users shall be able to login.
   * **1.1.2.2.** Registered users shall be able to share posts.
   * **1.1.2.3.** Registered users shall be able to search for posts, registered users and events.
   * **1.1.2.4.** Registered users shall be able to change his/her password and e-mail.
   * **1.1.2.5.** Registered users shall be able to leave a comment to a post and an event.
   * **1.1.2.6.** Registered users shall be able to like a post and an event.
   * **1.1.2.7.** Registered users shall be able to see a list of his/her posts in their profile page.
   * **1.1.2.8.** Registered users shall be able to see a list of posts and events that he/she liked.
    * **1.1.2.9. Special Registered Users**
        * **1.1.2.9.1.** Special Registered users shall be able to share events.
        * **1.1.2.9.2.** Special Registered users shall be able to see a list of his/her events in their profile page.

* **1.1.3. Post Features**
   * **1.1.3.1.** Registered Users shall be able to add photos to posts.
   * **1.1.3.2.** Registered Users shall be able to add audio to posts.
   * **1.1.3.3.** Registered Users shall be able to add video to posts.
   * **1.1.3.4.** Registered Users shall be able to add quote to posts.
   * **1.1.3.5.** Registered Users should be able to add tags to posts.
   * **1.1.3.6. For Special Registered Users**
      * **1.1.3.6.1.** Special Registered Users shall be able to add photos to events.
      * **1.1.3.6.2.** Special Registered Users shall be able to add audio to events.
      * **1.1.3.6.3.** Special Registered Users shall be able to add video to events.
      * **1.1.3.6.4.** Special Registered Users shall be able to add quote to events.
      * **1.1.3.6.5.** Special Registered Users should be able to add tags to events.

* **1.1.4. Search Conditions**
   * **1.1.4.1.** Users shall be able to search posts and events based on username.
   * **1.1.4.2.** Users shall be able to search posts and events based on a specific string in stories.
   * **1.1.4.3.** Users shall be able to search posts and events based on tags.

* **1.1.5. Homepage**
   * **1.1.5.1.** Homepage shall contain a map-view section where users can see previously posted posts in a map as pins.
   * **1.1.5.2.** Users can go to a specific location and see all the posts there int the map.

* **1.1.6. Profile page**
   * **1.1.6.1.** Users shall be able to see their posted posts in their profile pages.
   * **1.1.6.2.** Users should be able to edit his/her posts in their profile pages.
   * **1.1.6.3.** Users should be able to delete his/her posts in their profile pages.

### 1.2. System Requirements

* **1.2.1. Recommendation**
   * **1.2.1.1.** System shall recommend posts.
      * **1.2.1.1.1.** Recommendations shall be based on likes.
      * **1.2.1.1.2.** Recommendations shall be based on location.
      * **1.2.1.1.3.** Recommendations shall be based on tags.
      * **1.2.1.1.3.** Recommendations shall be based on tags.
      * **1.2.1.1.4.** Recommendations shall be based on the date of the post.
      * **1.2.1.1.5.** Recommendations shall be based on the story text itself.



## 2. Nonfunctional Requirements

* **2.1. Security**
   * **2.1.1.** Database system shall be protected.
   * **2.1.2.** Privacy of user data shall be protected.
   * **2.1.3.** Passwords shall be at least 8 characters long and contain at least one number and one letter.
   * **2.1.4.** Passwords shall be stored in encrypted format.

* **2.2 Availability**
   * **2.2.1.** The application is expected to have a web and mobile (Android) client.
   * **2.2.2.** The language of the application shall be in English.
   * **2.2.3.** Users shall navigate to every page within the application using at most 3 links.

* **2.3 Annotation**
   * **2.3.1.** The W3C Web Annotation Data Model shall be used to annotate items.

* **2.4 Performance**
   * **2.4.1** The system should be able to respond to requests within 3 second with at least 16 mbit internet speed.
