# Project Overview

## Title: D&D Cards

## Project Description

D&D cards is a support app for the popular dungeons and dragons 5th edition role playing game. Often the most difficult part of playing dungeons and dragons for news and experienced players is keeping track of all the rules and stats for your characters. This app seeks to make that experience as easy and streamlined as possible so the player can have a fun and fully immersive role playing experience.

While other apps aim to achieve similar goals, most are tied to the original character sheet and dice role model of game play. This app seeks to move to a purely card based system. When a player wants to perform an action all the player simply selects the action card they wish to play and all the character stats and dice roles needed for the action will be made automatically. A move that traditionally takes minutes now takes seconds, and with no math required! 

D&D Card makes onboard new players a breeze. Every D&D player knows the experience of finally convincing a friend to try D&D only to lose them as you spend hours explaining the rules. With class presets and the easy card interface,  you will be able to onboard a new player in a matter of minutes.

I hope you enjoyed your new immersive roleplaying experience with D&D Cards.


# Time/Priority Matrix
#### MVPs
##### Backend 
- User, Character models with proper relations
- Full CRUD routes for User Characters
- Full CRUD
- Seed Data with Character Presets and examples

##### Frontend
- React Architecture Setup
- Components
- - Landing
- - Sign UP
- - Login
- - About Page
- - Dashboard (displays action decks, basic charcter stats)
- - Character Details (shows greater details for background, bonds, etc...)
- - Character Leveling (Make leaving choices)
- - HP/Buff/Debuff Calculator (Add, Remove Damage, Select Buffs and Debuffs)
- - Character List (Characters user has created)
- - Footer (Paired down symbol-based stats bar)
- - Nav (Links to pages)
- - DeckCards (dispalys cards in deck)
- - Card (displays chosen Card in deck with details and action discription)

#### PostMVPs 
- 3rd Party Verification
- Allow Homebrew Customization
- Allow Personalized Avatar for Character
- Allow Users 
- Custom Card Designs
- Card Animations


#### MVP
| Component | Priority | Estimated Time | Time Invested | Actual Time |
| --- | :---: |  :---: | :---: | :---: |
|Planning|H|5||2:30:00|
Management Tasks|H|5||40:00:00
Frontend Setup|H|4||6:00:00
Layout/Nav/Footer|H|4||7:30:00
Landing|H|4||0:30:00
Dashboard|H|4||7:00:00
Deployment|H|4||4:00:00
Profile|H|4||3:00:00
Login|H|4||3:00:00
Connections|H|4||4:00:00
Signup|H|4||6:30:00
DeleteProfile|H|4||2:00:00
EditProfile|H|4||12:00:00
Matches|H|4||3:00:00
Styling|H|4||20:00:00
Backend Setup|H|25||6:00:00
BE Bug Fixes|H|25||5:00:00
Seed setup|H|25||1:00:00
Cascade Delete|H|25||3:00:00
Frontend Total|H|52||72:30:00
Backend|H|50:00:00||81:30:00
Overall Total|H|112:00:00||136:00:00

#### PostMVP
| Component | Priority | Estimated Time | Time Invested | Actual Time |
| --- | :---: |  :---: | :---: | :---: |
| Add additional criteria (idiom, language, secondary instrument, location, etc) | M | 2hr | -hr | -hr|
| Save matches/favorites | M | 6hr | -hr | -hr|
| Reviews of teachers | M | 6hr | -hr | -hr|
| Reviews of students | H | 6hr | -hr | -hr|
| Age ranges for students | L | 6hr | -hr | -hr|
| Search functionality | H | 10hr | -hr | -hr|
| Headshot or thumbnail| M | 6hr | -hr | -hr|
| Avatar | L | 6hr| -hr | -hr |
| Password functionality | L | 12hr | -hr | -hr|
| Track time of submission (newest on top) | H | 6hr | -hr | -hr|
| Total | H | 66hrs | -hrs | -hrs |

## Project Schedule

This schedule will be used to keep track of your progress throughout the week and align with our expectations.  
You are **responsible** for scheduling time with your squad to seek approval for each deliverable by the end of the corresponding day, excluding `Saturday` and `Sunday`.
| Day | Deliverable | Status
|---|---| ---|
|Day 1 - Fri|Project Proposal|Done
|Day 1 - Fri|Backend Repo|Done
|Day 1 - Fri|Frontend Repo|Done
|Day 1 - Fri|Create BE Basic File Structure|Done
|Day 1 - Fri|Create FE Basic File Structure|Done
|Day 1 - Fri|BE Placeholder Content|Done
|Day 1 - Fri|FE Placeholder Content|Done
|Stretch Goal|Deploy FE|Done
|Stretch Goal|Deploy BE|Done
|Day 2- Mon|BE Models|Done
|Day 2- Mon|BE Routes|Done
|Day 2- Mon|FE Component Mapping|Done
|Day 2- Mon|FE Component/File Fill|Done
|Day 2- Mon|FE Routes|Done
|Day 2- Mon|Re-Deploy FE/BE|Done
|Day 3 - Tues|FE Components|Complete
|Day 3 - Tues|Styling|Complete
|Day 3 - Tues|Re-Deploy FE/BE|Complete
|Day 4 - Wed|FE Component|Complete
|Day 4 - Wed|Styling|Complete
|Stretch Goal|Post-MVP Deliverables|Incomplete
|Day 4 - Wed|Re-Deploy FE/BE|Complete
|Day 5 - Thurs|Post-MVP Deliverables|Incomplete
|Day 5 - Thurs|Final deployment|Complete
|Day 5 - Thurs|Re-Deploy FE/BE|Complete
|Day 6 - Fri|Presentation|Complete



## User Stories
- Users want to create accounts, so they can access the app. 
- Users want to be able to update their account information in case anything changes. 
- Users want to be able to delete their account to keep their information private if they no longer wish to use Forte. 
- If the user is a teacher, they want to be matched with students that match certain criteria. 
- If the user is a student, they want to be matched with teachers hat match certain criteria
- Teacher users want to be able to search for students. 
- Student users want to be able to search for teachers. 
- Users want to have passwords to their accounts to feel secure. 
- Users like to make things personalized, they would like to add headshots or avatars. 
- Users want to have a timeline refresh to have the newest user match information on top.

## Deployment Links
- [Frontend](http://fortefound.surge.sh/)
- [Backend](https://p3-forte-backend.herokuapp.com/api/teachers)

## Project Board Links
- [WireFrames](https://res.cloudinary.com/dugmhtotn/image/upload/v1595610099/Mobile-Wireframes_m1vv7b.jpg)
- [Backend File Structer](https://res.cloudinary.com/dugmhtotn/image/upload/v1595609318/Backend-File-Structure_ngot1g.jpg)
- [Frontend File Structer](https://res.cloudinary.com/dugmhtotn/image/upload/v1595609325/Front-End-File-Structure_mguody.jpg)
- [Frontend Routes/Links](https://res.cloudinary.com/dugmhtotn/image/upload/v1595609336/Frontend-Routes-Links_agabqs.jpg)
- [React Framework](https://res.cloudinary.com/dugmhtotn/image/upload/v1595609355/React-Framwork_ivfom6.jpg)
- [State/Function Allocation](https://res.cloudinary.com/dugmhtotn/image/upload/v1595609363/StateFunction-Allocation_kjmywn.jpg)
- [GitHub Workflow](https://res.cloudinary.com/dugmhtotn/image/upload/v1595609346/GitHub-Workflow_k3x8sn.jpg)



## Languages and Libraries

React, JS, SCSS, Express, MongoDB, Mongoose, React-Router

## Issues and Resolutions

Use this section to list of all major issues encountered and their resolution.

#### Understanding Props.history
Spent a long time trying to re-route to a page within a handleSubmit function. Allie came in for the win on actually understanding that props.history contains the base url and then .push adds to that url. This effectivly re-routes the page.
```js
.then((res) => {
        props.history.push("/login");

```

#### Edit Profile
We all thought Edit Profile would be a quick component to complete. I was reusing the forms and a lot of the functionality Tyler had already written in SignUp.js. The issue I came across was displaying the updated information. Everyone on my team and Madeline helped with this problem. The line below is what I needed to not have an infinite loop. Travis was the one who ended up writing this key piece of information.

```js
.then(()=> setIsTeacherUpdated(false))
```
Another key piece was understanding how to pass in the data to the form imput so that the field values pre-populated correctly.
- setTeacherInput and setStudentInput where expecting an object

```js
  useEffect (()=>{
    setTeacherInput(activeUser[0])
    setStudentInput(activeUser[0])
  },[])
```
Below is the code in context

```js
const [studentInput, setStudentInput] = useState({
    firstName: "",
    lastName: "",
    email: "",
    idiom: "",
    language: "",
    location: "",
    other: "",
    student: true,
  });
  
  useEffect (()=>{
    setTeacherInput(activeUser[0])
    setStudentInput(activeUser[0])
  },[])
  const handleTeacherSubmit = (e) => {
    e.preventDefault();
    console.log("handle teacher submit");
    axios({
      url: `${apiUrl}/teachers/${activeUser[0]._id}`,
      method: "PUT",
      data: teacherInput,
    })
      .then(() => setIsTeacherUpdated(true))
      .catch(console.error);
  };
if(isTeacherUpdated){
  axios({url: `${apiUrl}/teachers/email/${activeUser[0].email}`})
    .then((res) => setActiveUser(res.data))
    .then(()=> setIsTeacherUpdated(false))
    .then(()=> props.history.push('/dashboard'))
    .catch(console.error) 
}

```

#### Connection Button
The connections button was especially tricky because of all the API calls and reloads it needed to perform:

- Add the student to the teacher's roster
- Add the teacher to the student's roster
- Re-assign ActiveUser so that the updated information loads throughout the app.
- Use logic to figure out if the person in question is a teacher or student

We were encountering an error that we had to reload the page to show the new information, and discovered after a few hours that two API paths were switched. 
```js
.then((res) => {
        // handle the "Connect!" button
  const handleConnectClick = () => {
    let connection = userProfile[0];
    if (connection !== undefined) {
      if (connection.student === true) {
        // add connection to activeUser's studentRoster
        const addToRoster = async () => {
          const response = await axios({
            url: `${apiUrl}/teachers/${activeUser[0]._id}/addStudent/${connection._id}`,
            method: "PUT",
          });
        };
        // add activeUser to connection's myTeachers
        const addToTeachers = async () => {
          const response = await axios({
            url: `${apiUrl}/students/${connection._id}/addTeacher/${activeUser[0]._id}`,
            method: "PUT",
          });
        };
        // re-assign activeUser
        const getTeacher = async () => {
          try {
            const response = await axios(
              `${apiUrl}/teachers/email/${activeUser[0].email}`
            );
            console.log("Profile getStudent: ", response);
            if (response.data.length > 0) {
              setActiveUser(response.data);
            }
          } catch (err) {
            console.error(err);
          }
        };
        const allTheThings = async () => {
          await addToRoster();
          await addToTeachers();
          await getTeacher();
        };
        allTheThings();

```
#### Cors Error on Deployment
We were getting a CORS error on the deployed site but not the local one. Allie figured out that we needed to turn our "origin" string into an array like so:
```js
var corsOptions = {
  origin: ["http://localhost:3000", "https://fortefound.surge.sh"],
  credentials: true,
  methods: ["GET", "POST", "OPTIONS", "PUT", "DELETE"],
};
app.use(cors(corsOptions));
 
```

# P3-GroupLab-ProjectMain

## Models

### Student

- firstName (String) (required)
- lastName (String)
- email (String) (required)
- location (String)
- idiom (String) (required)
- language (String)
- other (String)
- My Teaches (Array)
- online (Boolean)
- student/teacher (Boolean) (permanent)
- Teacher

### Teacher

- firstName (String) (required)