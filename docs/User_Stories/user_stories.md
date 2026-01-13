# Jira User Stories – Soma Membership Portal

---

| Story ID | User Role | User Story                                                                                                                   | Acceptance Criteria (Steps)                                                                                                                                                                                                                                 | Priority |
| -------- | --------- | ---------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------- |
| US-1.1   | New User  | As a new user, I want to register on the Soma website using my email so that I can start my membership registration process. | **Given** I am a new user on the Soma landing page<br>**When** I click the **Sign Up** button<br>**And** I enter my email, first name, last name, and password<br>**And** I click **Register**<br>**Then** a registration email is sent to my email address | Critical |

| Story ID | User Role       | User Story                                                                                                              | Acceptance Criteria (Steps)                                                                                                                                                                                             | Priority |
| -------- | --------------- | ----------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------- |
| US-1.2   | Registered User | As a registered user, I want to verify my email so that my account can be activated.                                    | **Given** I have received a registration email<br>**When** I click the verification link within 72 hours<br>**Then** I am redirected to the registration completion page<br>**And** the link becomes inactive after use | Critical |
| US-1.2a  | Registered User | As a registered user, I want to be notified if my verification link has expired so that I know to restart registration. | **Given** the verification link has expired<br>**When** I click the link after 72 hours<br>**Then** I see an expiry notification<br>**And** I am required to restart the registration process                           | High     |

| Story ID | User Role | User Story                                                                                                  | Acceptance Criteria (Steps)                                                                                                                                                                                                                                          | Priority |
| -------- | --------- | ----------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------- |
| US-1.3   | Member    | As a member, I want to complete my registration details so that I can gain access to the membership portal. | **Given** my email has been verified<br>**When** I enter my contact details, address, sex, and date of birth<br>**And** I upload my ID and visa documents<br>**Then** my details are submitted for verification<br>**And** I receive a registration completion email | Critical |


## Epic 2: Website & Navigation

| Story ID | User Story | Acceptance Criteria | Priority |
|--------|-----------|--------------------|----------|
| US-2.1 | As a user, I want to access the Soma website so that I can view general information. | Landing page loads with header and footer | Critical |
| US-2.2 | As a user, I want to view the About Us page so that I can learn about the organisation. | Content displayed correctly | High |
| Story ID | User Role | User Story                                                                                        | Acceptance Criteria (Steps)                                                                                                                                                                                                      | Priority |
| -------- | --------- | ------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------- |
| US-2.3   | Visitor   | As a visitor, I want to submit a contact enquiry so that I can communicate with the organisation. | **Given** I am on the Contact Us page<br>**When** I enter my name, valid email, and message<br>**And** I click **Submit**<br>**Then** the enquiry is emailed to the administrator<br>**And** a confirmation message is displayed | High     |
| US-2.3a  | Visitor   | As a visitor, I want to be notified if my email is invalid so that I can correct it.              | **Given** I enter an invalid or empty email address<br>**When** I click **Submit**<br>**Then** the form is not submitted<br>**And** a validation error message is shown                                                          | High     |

---

## Epic 3: Membership Portal

| Story ID | User Story | Acceptance Criteria | Priority |
|--------|-----------|--------------------|----------|
| US-3.1 | As a member, I want to view my profile so that I can see my personal information. | Profile details displayed | Critical |
| US-3.2 | As a member, I want to donate using my e-wallet so that I can support community projects. | Payment processed; receipt displayed | Critical |
| US-3.3 | As a user, I want to log in securely so that I can access the portal. | Valid credentials grant access | Critical |

---

## Epic 4: Community Projects

| Story ID | User Story | Acceptance Criteria | Priority |
|--------|-----------|--------------------|----------|
| US-4.1 | As a member, I want to request manager access so that I can manage projects. | Admin approval required; notification sent | High |
| US-4.2 | As a manager, I want to upload project content so that it can be reviewed. | Content uploaded; pending approval | Critical |
| US-4.3 | As an administrator, I want to approve project content so that it becomes visible. | Content approved and published | Critical |

---

## Epic 5: Loan Requests

| Story ID | User Story | Acceptance Criteria | Priority |
|--------|-----------|--------------------|----------|
| US-5.1 | As a member, I want to submit a loan request so that I can receive financial support. | Loan form submitted; admin notified | Critical |

