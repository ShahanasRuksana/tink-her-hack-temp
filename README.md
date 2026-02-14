<p align="center">
  <img src="./img.png" alt="Project Banner" width="100%">
</p>

# Walk With Me 🎯

## Basic Details

### Team Name: LYORA

### Team Members
- Member 1: Shahanas Ruksana C P - jYOTHI ENGINEERING COLLEGE
- Member 2: Sahla Nasrin CP

### Hosted Project Link
https://deluxe-conkies-3f9a16.netlify.app/

### Project Description
"Walk With Me: Stay safe on every walk. If you don’t check in, your trusted contacts get your live location instantly."

### The Problem statement
“Walk With Me monitors your walk and sends automatic alerts to trusted contacts with your live location if you don’t confirm you’re safe.”

### The Solution
“Walking alone can feel unsafe, stressful, and unpredictable. Our app ‘Walk With Me’ ensures your safety by alerting trusted contacts with your live location if you don’t check in.”

---

## Technical Details

### Technologies/Components Used

**For Software:**
- Languages used:  JavaScript, HTML,CSS
- Frameworks used: none
- Libraries used: none
- Tools used: VS Code,Web Browser,Window OS

**For Hardware:**
- Main components: none
- Specifications: none
- Tools required: none

---

## Features

List the key features of your project:
- Feature 1: User Signup – Users can register with basic details and prepare emergency information
- Feature 2: Add Trusted Contacts – Save phone numbers or emails of family/friends
- Feature 3: Start Walk Timer – Begin a safety timer while travelling or walking.
- Feature 4: Safety Check Popup – After a fixed time, the system asks “Are you safe?”.Auto Alert – If no response, emergency contacts are notified.
Live Location Sharing – Sends current GPS location to trusted people.
Emergency Button – Quick way to trigger help instantly.

---

## Implementation

### For Software:

#### Installation
```bash
Download or clone the repository to your computer.
```

#### Run
```bash
Open index.html in your browser.
```

### For Hardware:

#### Components Required
none

#### Circuit Setup


---

## Project Documentation

### For Software:

#### Screenshots (Add at least 3)


<img width="1366" height="768" alt="Screenshot (2)" src="https://github.com/user-attachments/assets/ae7fd490-6d94-4698-bef2-cf0f68a87903" />

<img width="1366" height="768" alt="Screenshot (3)" src="https://github.com/user-attachments/assets/ebe9cb7a-f34f-455e-9d91-2c15e70f2bce" />


<img width="1366" height="768" alt="Screenshot (4)" src="https://github.com/user-attachments/assets/2ef9acc0-0f83-4db1-b9e8-6731c8505725" />


#### Diagrams

**System Architecture:**
The Walk With Me system is a browser-based safety monitoring platform designed to protect users while they travel alone.

#### Components

1. **Frontend (Client Side)**
   - Built using HTML, CSS and Vanilla JavaScript.
   - Provides UI for signup, adding emergency contacts, starting the walk timer, and responding to safety check popups.

2. **Location Service**
   - Uses the browser Geolocation API to fetch the user's live GPS coordinates.

3. **Timer Engine**
   - Runs a background countdown (for example, every 5 minutes).
   - Triggers the safety confirmation popup.

4. **Alert System**
   - Activated if the user does not respond.
   - Collects live location and prepares alert messages.

5. **Communication Module**
   - Sends SMS and Email notifications to saved emergency contacts.

6. **Data Storage**
   - Stores basic user profile and contact information (can be local storage or database depending on deployment).

---

#### Data Flow

User → starts walk → timer runs → popup asks “Are you safe?”  
If YES → timer resets.  
If NO or no response → GPS location fetched → alert message generated → SMS/Email sent to emergency contacts.

---

#### Tech Stack

- HTML – structure  
- CSS – styling & responsive design  
- JavaScript – logic, timer, geolocation  
- SMS/Email API – alert communication  
- Browser Local Storage / Backend DB – saving user data

---

#### Interaction Between Components

The frontend triggers the timer.  
The timer triggers the popup.  
If ignored, the system calls the geolocation service.  
The communication module then sends alerts with the retrieved coordinates.

**Application Workflow:**

### Application Workflow

The application is designed to work in simple, clear steps so users can activate safety monitoring quickly.

1. User opens the Walk With Me website.
2. Welcome screen with motivation and “Get Started” button appears.
3. User signs up and adds emergency contacts.
4. User presses **Start Walk**.
5. The safety timer begins running.
6. After the selected interval, a popup asks:
   **“Are you safe?”**

---

#### Possible Outcomes

✅ **User presses YES**
- Timer resets.
- Monitoring continues.

⚠️ **User presses NO or gives no response**
- System automatically fetches live GPS location.
- Emergency alert message is generated.
- SMS and Email are sent to saved contacts.
- Contacts can track or call the user.

---

#### Goal of Workflow

To ensure that if a user becomes unable to respond, the system reacts automatically and informs trusted people without delay.

---

### For Hardware:

#### Schematic & Circuit

![Circuit](Add your circuit diagram here)
*Add caption explaining connections*

![Schematic](Add your schematic diagram here)
*Add caption explaining the schematic*

#### Build Photos

![Team](Add photo of your team here)

![Components](Add photo of your components here)
*List out all components shown*

![Build](Add photos of build process here)
*Explain the build steps*

![Final](Add photo of final product here)
*Explain the final build*

---

## Additional Documentation

### For Web Projects with Backend:

#### API Documentation

**Base URL:** `https://api.yourproject.com`

##### Endpoints

**GET /api/endpoint**
- **Description:** [What it does]
- **Parameters:**
  - `param1` (string): [Description]
  - `param2` (integer): [Description]
- **Response:**
```json
{
  "status": "success",
  "data": {}
}
```

**POST /api/endpoint**
- **Description:** [What it does]
- **Request Body:**
```json
{
  "field1": "value1",
  "field2": "value2"
}
```
- **Response:**
```json
{
  "status": "success",
  "message": "Operation completed"
}
```

[Add more endpoints as needed...]

---

### For Mobile Apps:

#### App Flow Diagram

![App Flow](docs/app-flow.png)
*Explain the user flow through your application*

#### Installation Guide

**For Android (APK):**
1. Download the APK from [Release Link]
2. Enable "Install from Unknown Sources" in your device settings:
   - Go to Settings > Security
   - Enable "Unknown Sources"
3. Open the downloaded APK file
4. Follow the installation prompts
5. Open the app and enjoy!

**For iOS (IPA) - TestFlight:**
1. Download TestFlight from the App Store
2. Open this TestFlight link: [Your TestFlight Link]
3. Click "Install" or "Accept"
4. Wait for the app to install
5. Open the app from your home screen

**Building from Source:**
```bash
# For Android
flutter build apk
# or
./gradlew assembleDebug

# For iOS
flutter build ios
# or
xcodebuild -workspace App.xcworkspace -scheme App -configuration Debug
```

---

### For Hardware Projects:

#### Bill of Materials (BOM)

| Component | Quantity | Specifications | Price | Link/Source |
|-----------|----------|----------------|-------|-------------|
| Arduino Uno | 1 | ATmega328P, 16MHz | ₹450 | [Link] |
| LED | 5 | Red, 5mm, 20mA | ₹5 each | [Link] |
| Resistor | 5 | 220Ω, 1/4W | ₹1 each | [Link] |
| Breadboard | 1 | 830 points | ₹100 | [Link] |
| Jumper Wires | 20 | Male-to-Male | ₹50 | [Link] |
| [Add more...] | | | | |

**Total Estimated Cost:** ₹[Amount]

#### Assembly Instructions

**Step 1: Prepare Components**
1. Gather all components listed in the BOM
2. Check component specifications
3. Prepare your workspace
![Step 1](images/assembly-step1.jpg)
*Caption: All components laid out*

**Step 2: Build the Power Supply**
1. Connect the power rails on the breadboard
2. Connect Arduino 5V to breadboard positive rail
3. Connect Arduino GND to breadboard negative rail
![Step 2](images/assembly-step2.jpg)
*Caption: Power connections completed*

**Step 3: Add Components**
1. Place LEDs on breadboard
2. Connect resistors in series with LEDs
3. Connect LED cathodes to GND
4. Connect LED anodes to Arduino digital pins (2-6)
![Step 3](images/assembly-step3.jpg)
*Caption: LED circuit assembled*

**Step 4: [Continue for all steps...]**

**Final Assembly:**
![Final Build](images/final-build.jpg)
*Caption: Completed project ready for testing*

---

### For Scripts/CLI Tools:

#### Command Reference

**Basic Usage:**
```bash
python script.py [options] [arguments]
```

**Available Commands:**
- `command1 [args]` - Description of what command1 does
- `command2 [args]` - Description of what command2 does
- `command3 [args]` - Description of what command3 does

**Options:**
- `-h, --help` - Show help message and exit
- `-v, --verbose` - Enable verbose output
- `-o, --output FILE` - Specify output file path
- `-c, --config FILE` - Specify configuration file
- `--version` - Show version information

**Examples:**

```bash
# Example 1: Basic usage
python script.py input.txt

# Example 2: With verbose output
python script.py -v input.txt

# Example 3: Specify output file
python script.py -o output.txt input.txt

# Example 4: Using configuration
python script.py -c config.json --verbose input.txt
```

#### Demo Output

**Example 1: Basic Processing**

**Input:**
```
This is a sample input file
with multiple lines of text
for demonstration purposes
```

**Command:**
```bash
python script.py sample.txt
```

**Output:**
```
Processing: sample.txt
Lines processed: 3
Characters counted: 86
Status: Success
Output saved to: output.txt
```

**Example 2: Advanced Usage**

**Input:**
```json
{
  "name": "test",
  "value": 123
}
```

**Command:**
```bash
python script.py -v --format json data.json
```

**Output:**
```
[VERBOSE] Loading configuration...
[VERBOSE] Parsing JSON input...
[VERBOSE] Processing data...
{
  "status": "success",
  "processed": true,
  "result": {
    "name": "test",
    "value": 123,
    "timestamp": "2024-02-07T10:30:00"
  }
}
[VERBOSE] Operation completed in 0.23s
```

---

## Project Demo

### Video
[Add your demo video link here - YouTube, Google Drive, etc.]

*Explain what the video demonstrates - key features, user flow, technical highlights*

### Additional Demos
[Add any extra demo materials/links - Live site, APK download, online demo, etc.]

---

## AI Tools Used (Optional - For Transparency Bonus)

If you used AI tools during development, document them here for transparency:

**Tool Used:** [e.g., GitHub Copilot, v0.dev, Cursor, ChatGPT, Claude]

**Purpose:** [What you used it for]
- Example: "Generated boilerplate React components"
- Example: "Debugging assistance for async functions"
- Example: "Code review and optimization suggestions"

**Key Prompts Used:**
- "Create a REST API endpoint for user authentication"
- "Debug this async function that's causing race conditions"
- "Optimize this database query for better performance"

**Percentage of AI-generated code:** [Approximately X%]

**Human Contributions:**
- Architecture design and planning
- Custom business logic implementation
- Integration and testing
- UI/UX design decisions

*Note: Proper documentation of AI usage demonstrates transparency and earns bonus points in evaluation!*

---

## Team Contributions

- [Name 1]: [Specific contributions - e.g., Frontend development, API integration, etc.]
- [Name 2]: [Specific contributions - e.g., Backend development, Database design, etc.]
- [Name 3]: [Specific contributions - e.g., UI/UX design, Testing, Documentation, etc.]

---

## License

This project is licensed under the [LICENSE_NAME] License - see the [LICENSE](LICENSE) file for details.

**Common License Options:**
- MIT License (Permissive, widely used)
- Apache 2.0 (Permissive with patent grant)
- GPL v3 (Copyleft, requires derivative works to be open source)

---

Made with ❤️ at TinkerHub
