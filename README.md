# resume_analyzer_with-nlp


This Streamlit application, named **"Smart Resume Analyser"**, helps clients transfer and investigate their resumes, giving customized suggestions in view of their abilities and content.

### Key Elements:

1. **Resume Transfer and Display**:
   - Clients can transfer their resume in PDF design. The application saves and shows the resume for additional examination.

2. **Resume Analysis**:
   - Separates key data like name, email, and contact subtleties.
   - Decides the client's vocation level (Fresher, Halfway, Experienced) in light of the quantity of resume pages.

3. **Skill and Course Recommendations**:
   - Dissects the abilities recorded in the resume and coordinates them with predefined watchwords for different fields (Information Science, Web Advancement, Android Improvement, iOS Advancement, UI-UX Advancement).
   - Gives suggested abilities and important courses in view of the recognized field.

4. **Resume Improvement Tips**:
   - Assesses the resume content and proposes enhancements. Gives scores in view of the consideration of segments like Goal, Statement, Leisure activities, Accomplishments, and Undertakings.

5. **Data Capacity and Management**:
   - Stores client information in a MySQL data set, including resume scores and suggestions. Administrator clients can see and download client information.

6. **Admin Interface**:
   - Administrators can sign in with certifications and access an information outline, all things considered. They can see and download a CSV report of client information.

### Innovation Utilized:
- **Streamlit**: For the web interface.
- **PDFMiner and Pyresparser**: For continue parsing.
- **Pymysql**: For data set activities.
- **Pafy and YouTube_dl**: For bringing YouTube video titles.
- **Plotly**: For information representation.

The application incorporates continue examination with customized suggestions and administrator functionalities, meaning to improve work looking for procedures.
