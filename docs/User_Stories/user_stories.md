# Jira User Stories – Soma Membership Portal

---
## Epic 1: Member Self-Registration

| Story ID | User Role       | User Story                                                                                                                   | Acceptance Criteria (Steps)                                                                                                                                                                                                                                   | Priority |
| -------- | --------------- | ---------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------- |
| US-1.1   | New User        | As a new user, I want to register on the Soma website using my email so that I can start my membership registration process. | **Given** I am a new user on the Soma landing page<br>**When** I click the **Sign Up** button<br>**And** I enter my email, first name, last name, and password<br>**And** I click **Register**<br>**Then** a registration email is sent to my email address   | Critical |
| US-1.2   | Registered User | As a registered user, I want to verify my email so that my account can be activated.                                         | **Given** I have received a registration email<br>**When** I click the verification link within 72 hours<br>**Then** I am redirected to the registration completion page<br>**And** the link becomes inactive after use                                       | Critical |
| US-1.3   | Registered User | As a registered user, I want to be notified if my verification link has expired so that I know to restart registration.      | **Given** the verification link has expired<br>**When** I click the link after 72 hours<br>**Then** I see an expiry notification<br>**And** I am required to restart the registration process                                                                 | High     |
| US-1.4   | Member          | As a member, I want to complete my registration details so that I can gain full access to the membership portal.             | **Given** my email has been verified<br>**When** I enter my contact details, address, sex, and date of birth<br>**And** I upload my ID and visa documents<br>**Then** my registration is submitted for verification<br>**And** I receive a confirmation email | Critical |



## Epic 2: Website & Navigation

| Story ID | User Role | User Story                                                                                                     | Acceptance Criteria (Steps)                                                                                                                                                                                                      | Priority |
| -------- | --------- | -------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------- |
| US-2.1   | Visitor   | As a visitor, I want to access the Soma website so that I can view general information about the organisation. | **Given** I enter the Soma website URL<br>**When** the page loads<br>**Then** I see the landing page<br>**And** the header and footer are visible                                                                                | Critical |
| US-2.2   | Visitor   | As a visitor, I want to view the About Us page so that I can learn about the organisation.                     | **Given** I am on the landing page<br>**When** I click **About Us**<br>**Then** I am redirected to the About Us page<br>**And** organisational information is displayed                                                          | High     |
| US-2.3   | Visitor   | As a visitor, I want to submit a contact enquiry so that I can communicate with the organisation.              | **Given** I am on the Contact Us page<br>**When** I enter my name, valid email, and message<br>**And** I click **Submit**<br>**Then** the enquiry is emailed to the administrator<br>**And** a confirmation message is displayed | High     |
| US-2.4   | Visitor   | As a visitor, I want to see validation errors so that I can correct my contact form submission.                | **Given** I enter an invalid or empty email address<br>**When** I click **Submit**<br>**Then** the form is not submitted<br>**And** an error message is displayed                                                                | High     |


---

## Epic 3: Membership Portal

| Story ID | User Role | User Story                                                                                            | Acceptance Criteria (Steps)                                                                                                                                                                     | Priority |
| -------- | --------- | ----------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------- |
| US-3.1   | Member    | As a member, I want to log in to the Soma Membership Portal so that I can access my account.          | **Given** I have valid login credentials<br>**When** I enter my email and password<br>**And** I click **Login**<br>**Then** I am redirected to the portal landing page                          | Critical |
| US-3.2   | Member    | As a member, I want to see an error message so that I know my login attempt failed.                   | **Given** I enter invalid credentials<br>**When** I click **Login**<br>**Then** an error message is displayed                                                                                   | High     |
| US-3.3   | Member    | As a member, I want to view my profile so that I can see my personal information.                     | **Given** I am logged in<br>**When** I click **Profile**<br>**Then** my personal and contact details are displayed                                                                              | Critical |
| US-3.4   | Member    | As a member, I want to create an e-wallet so that I can link my bank account.                         | **Given** I am logged in<br>**When** I navigate to the Payment section<br>**And** I enter my debit or credit card details<br>**Then** my payment method is saved securely                       | Critical |
| US-3.5   | Member    | As a member, I want to make a donation using my e-wallet so that I can support community initiatives. | **Given** I have an active e-wallet<br>**When** I select a donation amount<br>**And** I confirm payment<br>**Then** the transaction is processed<br>**And** a confirmation message is displayed | Critical |


---

## Epic 4: Community Projects

| Story ID | User Role     | User Story                                                                                         | Acceptance Criteria (Steps)                                                                                                                                                                 | Priority |
| -------- | ------------- | -------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------- |
| US-4.1   | Member        | As a member, I want to request manager access so that I can manage community projects.             | **Given** I am logged in as a member<br>**When** I submit a manager access request<br>**Then** the request is sent to the administrator<br>**And** I receive a submission notification      | High     |
| US-4.2   | Manager       | As a manager, I want to upload community project content so that it can be reviewed and published. | **Given** I am logged in as a manager<br>**When** I upload project documents, images, and descriptions<br>**And** I click **Publish**<br>**Then** the content is marked as pending approval | Critical |
| US-4.3   | Administrator | As an administrator, I want to approve project content so that it becomes visible to users.        | **Given** I have pending approval requests<br>**When** I review and approve the content<br>**Then** the project is published<br>**And** the manager is notified                             | Critical |


---

## Epic 5: Loan Requests

| Story ID | User Role | User Story                                                                               | Acceptance Criteria (Steps)                                                                                                                                                                    | Priority |
| -------- | --------- | ---------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------- |
| US-5.1   | Member    | As a member, I want to submit a loan request so that I can receive financial assistance. | **Given** I am logged in to the portal<br>**When** I complete the loan request form<br>**And** I click **Submit**<br>**Then** the request is recorded<br>**And** the administrator is notified | Critical |

