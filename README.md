# General Questions

####  **1.	What is the primary purpose of Quality Assurance (QA)?**

The primary purpose of Quality Assurance (QA) is to ensure that a product, service, or system meets specified requirements and quality standards. QA focuses on preventing defects during the development process by implementing structured processes, methodologies, and best practices.

Key objectives of QA include:

**Consistency:** Ensure that the product performs reliably under various conditions and meets user expectations.

**Defect Prevention:** Identify and address potential issues early in the development lifecycle to avoid costly fixes later.

**Process Improvement:** Enhance the efficiency and effectiveness of development processes to achieve higher quality outcomes.

**Compliance:** Ensure adherence to regulatory, industry, and company standards.
Customer Satisfaction: Deliver a product that fulfills user needs, providing a positive experience and building trust.

QA differs from testing in that it is process-oriented, focusing on building quality into the product from the start, while testing is product-oriented, verifying that the final product works as intended.

#### **2.	What is the difference between a test case and a test plan?**

A test plan is a strategic document that outlines the overall approach, scope, objectives, resources, schedule, and activities for testing a project. It serves as a roadmap for the testing process.

A test case, on the other hand, is a detailed document that specifies individual testing scenarios, including input data, execution steps, expected outcomes, and pass/fail criteria, used to validate specific functionality or requirements of the application.

#### **3.	What does the term 'regression testing' refer to?**

Regression testing refers to the process of re-executing test cases to ensure that recent changes, such as code updates, bug fixes, or feature additions, have not introduced new defects or negatively impacted existing functionality.


#### **4.	How would you create a template to describe bugs on a software that is being constantly released?**

I would create a model that follows the following structure:

**Bug ID & Title:** A unique identifier and a brief, clear title.
**Environment:** Details such as OS, app version, device type, and release version.
**Steps to Reproduce:** A step-by-step guide to recreate the issue.
**Expected vs. Actual Behavior:** A comparison of what should happen vs. what occurs.
**Severity & Frequency:** The bug’s impact on functionality and how often it happens.
**Logs/Screenshots:** Relevant error logs, stack traces, or visual evidence.
**Regression:** Indication if the bug is new or has appeared after a recent release.
**Workaround:** Any temporary solutions or alternatives.
**Impact:** The effect on user experience or business operations.
**Status & Assigned To:** The current status of the bug and the person responsible for fixing it.


#### **5.	 What is the importance of test automation in QA? What would you explore in terms ofautomation for games being developed in a short period of time?**

Test automation is crucial in Quality Assurance (QA) because it increases efficiency, consistency, and coverage while reducing human error and the time spent on repetitive testing tasks. It allows teams to run more tests in less time, detect issues early, and maintain high-quality standards throughout development.
For games developed in a short period, I would explore automation for regression testing, performance testing, and compatibility testing across different devices and platforms. Automated tests could cover gameplay mechanics, UI/UX consistency, load times, and stability under various conditions, ensuring that the game is polished and bug-free before release, despite the limited timeframe.

#### **6.	Describe the main stages of the Software Testing Life Cycle (STLC).**

The Software Testing Life Cycle (STLC) includes several key stages. It starts with requirement analysis, where testers review the project’s requirements to identify testable components. Next, test planning is done to outline the scope, objectives, resources, and timelines for testing. Test cases and scripts are then designed based on the requirements. Once the test environment is set up, tests are executed, and defects are logged and tracked. Finally, the testing process is closed after executing all tests, resolving defects, and documenting the results and lessons learned for future projects.

####  **7. How would you handle a situation where a bug you reported is marked as 'not reproducible' by the development team?**

If a bug I reported is marked as "not reproducible" by the development team, I would first recheck the issue on my end to confirm it's still happening, ensuring the same steps and environment are followed. I would then gather additional information like logs, screenshots, or videos to provide more context. I would also clarify the test environment and steps to reproduce, checking for any discrepancies. If needed, I'd collaborate closely with the development team to troubleshoot and resolve the issue, offering to walk through the process together. If the issue persists, I would escalate with further details to ensure it gets the attention it needs.

 
# Hands-On Test

## Functional Testing

**Title:**  Verify that the game loads properly on different browsers (Chrome, Firefox, Safari, Edge).

**Preconditions:**
•	The game is published and accessible via the URL.
•	User has access to a stable internet connection.
•	Browsers (Chrome, Firefox, Edge) are installed on the testing machine.

**Test Steps:**
1.	Open Chrome browser.
2.	Navigate to the game’s URL.
3.	Wait for the game to fully load.
4.	Repeat steps 1–3 for Firefox, Safari, and Edge browsers.

**Expected Result:**
•	The game should load correctly and fully on all four browsers (Chrome, Firefox, Safari, Edge).
•	No major visual or functional issues should be present, and the game should be playable (e.g., no missing assets, buttons, or functionality).

**Postconditions:**
•	The game is accessible and functioning properly across the four tested browsers.

### **- Chrome** 
https://youtu.be/JAq4Fb3hXLU
     


![Image](https://github.com/user-attachments/assets/1ce8d0ab-7b5d-4fe8-9ef2-afdc6170f470)
![Image](https://github.com/user-attachments/assets/6e0381fa-02a6-4f53-b8bc-80681cb78191)
![Image](https://github.com/user-attachments/assets/48853c54-263a-4718-b95e-8d12f6ec0501)
![Image](https://github.com/user-attachments/assets/5dbca801-c550-4ac1-ac40-ac00b813fe4f)


### **- Firefox**
https://youtu.be/VnT3wZQTeCQ

![Image](https://github.com/user-attachments/assets/dfb0d620-e22a-4917-ab7a-489dde32cd0f)
![Image](https://github.com/user-attachments/assets/402ebe56-5ca6-46c9-9a34-5e3dc373581d)
![Image](https://github.com/user-attachments/assets/e8a22d99-c0c4-481a-bfc3-be6e930659a5)
![Image](https://github.com/user-attachments/assets/ad557151-7d0c-4367-b32f-1bb0672e5024)

### **- Edge**
https://youtu.be/1lsQ0qzLNBQ 

![Image](https://github.com/user-attachments/assets/83580227-24b9-423b-bf9f-9a2f20e1309c)
![Image](https://github.com/user-attachments/assets/d2b85ede-6743-4187-996c-f88bd59cc59e)
![Image](https://github.com/user-attachments/assets/adae271b-6ac7-45cc-a0a8-5688b4917d3b)
![Image](https://github.com/user-attachments/assets/c13edf9c-7396-4bb2-b7a9-a73b03279f2a)

 

 ### **- Brave**
https://youtu.be/OEHkuA4w5fM

![Image](https://github.com/user-attachments/assets/dbafeb8d-5651-446f-9f37-6d60541cd917)
![Image](https://github.com/user-attachments/assets/b220af4b-7a0f-45fd-94c7-6c15abf51dec)
![Image](https://github.com/user-attachments/assets/d0b37820-4521-43d6-a2c5-a0856cda9742)
![Image](https://github.com/user-attachments/assets/fbd9a23e-9daf-4d55-b6f3-53a83cee7505)



## Usability Testing:

**Title:** Evaluate the game's user interface for ease of use and test responsiveness across different screen sizes (desktop, tablet, mobile).

**Preconditions:**
•	The game is accessible and functional on the testing device.
•	The game is properly installed or available through a web browser.

**Test Steps:**
1.	Launch the game on a desktop screen and evaluate the user interface (UI) for clarity, ease of navigation, and overall usability.
2.	Launch the game on a tablet and assess if the UI elements adjust appropriately for the screen size and if the interface is still user-friendly.
3.	Launch the game on a mobile device and check if the game’s UI remains responsive, readable, and easy to navigate, with no elements cut off or overly compressed.
4.	Test common actions such as starting a new game, accessing settings, and navigating through the menus on all screen sizes (desktop, tablet, mobile).

**Expected Result:**
•	The game should have a clear, easy-to-use UI on all devices (desktop, tablet, mobile).
•	UI elements should resize or reposition appropriately on different screen sizes to ensure the game is usable and visually appealing.
•	There should be no issues with responsiveness, such as overlapping text or cut-off buttons, across any device.

**Postconditions:**
•	The game should provide a smooth user experience with a UI that adapts correctly to various screen sizes (desktop, tablet, mobile).

### **Desktop – Windonws 11**
 
https://youtu.be/OEHkuA4w5fM

![Image](https://github.com/user-attachments/assets/992f7a82-ff79-461a-a92a-92a3ace32f82)
![Image](https://github.com/user-attachments/assets/20143a9e-aca2-47fc-9cf0-94eed4ab6503)
![Image](https://github.com/user-attachments/assets/17786ed8-123b-443d-b768-fd83bb6e8f2e)
![Image](https://github.com/user-attachments/assets/0c05a378-637d-4594-a8dd-8fa136bf4467)
![Image](https://github.com/user-attachments/assets/c0d2861f-d54c-4709-a6dd-cc28f42588c6)


### **Mobile – Android 12**
https://youtu.be/n_jx0zROBoY

![Image](https://github.com/user-attachments/assets/6437e745-06e3-4ef7-ae2c-be1b558d5846)
![Image](https://github.com/user-attachments/assets/5dcc3200-f9dc-42a0-b3f5-4b10f0c2dc12)
![Image](https://github.com/user-attachments/assets/49c34e85-0a40-48d6-a391-cd047096da31)
![Image](https://github.com/user-attachments/assets/249901f8-9a43-4622-8d9d-5be8752cdc6c)


### **Mobile –  Tablet**
https://youtu.be/QsrNE7cqlrA

Since I did not use a real tablet but rather Google Chrome for the test, the result may not have been as expected. 


![Image](https://github.com/user-attachments/assets/c7b83752-b8ad-4559-a70a-be5a26a94c79)
![Image](https://github.com/user-attachments/assets/262effde-dadd-470a-ace5-d2b15859ffb0)
![Image](https://github.com/user-attachments/assets/9a577793-fb40-4332-8a87-9227bcf95421)
![Image](https://github.com/user-attachments/assets/479bb733-e0fe-4d9f-8bff-d25afd6abd61)



## Performance Testing:
**Title:** Monitor the game’s performance (e.g., loading times, frame rates) under normal and heavy loads.

**Preconditions:**
•	The game is installed or accessible via a web browser.
•	A stable internet connection is available (if applicable).
•	Performance monitoring tools are set up to track loading times, frame rates, and other relevant metrics.
•	The game is ready for testing under normal and heavy load conditions.

**Test Steps:**

**1.	Normal Load Testing:**
o	Launch the game under normal usage conditions (e.g., minimal players or basic game features activated).
o	Monitor and record key performance metrics such as loading times, frame rates, and overall responsiveness during gameplay.

**2.	Heavy Load Testing:**
o	Simulate a heavy load by increasing the number of players, activating high-demand game features, or running the game in a resource-heavy environment (e.g., multiple applications running simultaneously).
o	Record and compare performance metrics, focusing on loading times, frame rates, and any signs of lag or performance degradation.

3.	Test various in-game actions under both normal and heavy loads (e.g., opening menus, switching between game modes, loading new levels) to observe any changes in performance.

4.	Repeat the tests on different devices or configurations if applicable (e.g., desktop, tablet, mobile).


**Expected Result:**
•	Under normal load, the game should load within acceptable times (e.g., less than 5 seconds), and the frame rate should remain stable, without significant drops or lag.
•	Under heavy load, the game should still function without crashing or showing excessive lag, although slight drops in frame rate or longer loading times may be acceptable.
•	The game should maintain a playable experience, with no critical performance issues impacting gameplay.

**Postconditions:**
•	Performance data is captured, and any performance bottlenecks or issues are identified for optimization.

### **Normal Load Testing**
![Image](https://github.com/user-attachments/assets/3616d6d7-5ebc-4efc-975e-afeb93945670)


### **Heavy Load Testing**
 ![Image](https://github.com/user-attachments/assets/030da3d0-3adb-4ef1-9892-be5672568e0d)





## **Report Findings**

**Bug Title:** Mute function does not stop sound when volume is muted, only stops when the tab is closed and reopened.

**Steps to Reproduce the Bug:**
1.	Open the game in your browser or application.
2.	Wait for the game to fully load.
3.	In the game’s main menu, locate the volume control (typically in settings or the audio control bar).
4.	Click the mute icon or slide the volume control to 0% to mute the sound.
5.	Observe the sound of the game continuing to play, even though the volume is muted.
6.	To check the issue, close the game tab or application completely.
7.	Reopen the tab or game application and verify if the sound remains muted (now the sound should stop correctly when reopening the game).

**Bug Severity:**
High – The sound of the game should not continue after being muted. The fact that the user has to close the tab to resolve this issue can be a critical flaw in user experience, especially if players are trying to play in a quiet environment.

**Expected Result:**
When the user clicks the mute button or adjusts the volume control to 0%, the game’s sound should immediately stop playing. The sound should not continue, even after the volume change. The sound should only be restored if the user unmutes manually or adjusts the volume again. There should be no need to close the tab or restart the game for mute to work correctly.

https://youtu.be/PJVlPdktitk
 
![Image](https://github.com/user-attachments/assets/0777afee-fd81-4ebf-8c1d-7f1359f5d1c6)
![Image](https://github.com/user-attachments/assets/b6d084b8-5c2f-4c12-87f6-d0da02f6a1db)
![Image](https://github.com/user-attachments/assets/ffdb7db0-6a12-4db2-af24-9fcdc450378f)

 
 

# **General Overview**

**Even though this is not a question, we’d like to hear why you selected this game. What are the ups and downs?**
The reason I chose this game is because of its captivating "Día de los Muertos" theme, which really draws me in. The vibrant design and the immersive music are definite highlights, as they create an engaging atmosphere that keeps you hooked. However, one downside would be the lack of more impactful effects or feedback when scoring points. It would enhance the overall experience if there were more rewarding visual or audio cues when achieving milestones.

**What would you consider a factor that would make you play again?**
Yes, I would consider playing again because the game offers the potential for consecutive wins, which makes it more exciting and motivates you to keep playing. Additionally, the engaging design with its vibrant visuals and immersive theme adds to the overall enjoyment, making the experience even more captivating and encouraging me to return.

**Was this an engaging experience?**
Yes, it was definitely an engaging experience. The game's vibrant design and immersive Día de los Muertos theme created a visually captivating atmosphere, while the exciting mechanics, such as the cascading symbols and the potential for consecutive wins, kept the gameplay dynamic and unpredictable. This combination of visuals, sound, and rewarding features made it enjoyable and kept me hooked throughout the session.

