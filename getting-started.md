# Getting Started with the insidepacket NaaS Portal

This guide will walk you through the initial steps of setting up your account and managing users within the insidepacket NaaS Portal.

## 1. Account Setup

Getting started with the insidepacket portal is simple.

1.  **Sign Up:** Once you have signed up, you will receive an email to verify your email address.
2.  **Set Password & Details:** Next, set up a password and complete a couple of personal and company details.
3.  **Account Administrator:** If you registered your company on the portal, you will automatically be assigned the Account Administrator role.
4.  **Joining an Existing Company:** If you are joining a company already registered on the portal, contact your Account Administrator to assign you appropriate roles and permissions.

## 2. Adding a Team Member

As an Account Administrator, you can easily add new team members and assign them roles.

1.  **Log in to the NaaS Portal:** Use your Tenant’s credentials to sign in.
2.  **Navigate to the Tenant Tab:** On the left-hand side menu, click on `Tenant`.
3.  **Access the Users Section:** Under the `Tenant` tab, select `Users`.
4.  **Add New User:** Click the `+Add` button to create a new user.
5.  **Complete User Details (Section 1):**
    * **Username:** Enter a unique username (should not contain capital letters).
    * **Email:** Provide a valid email address.
    * **Role:** Choose the user role (Admin or User).
    * **Tenant:** Select the associated tenant.
    * **Phone:** Enter a phone number (optional).
    * **Status:** Set user status as Active or Inactive.
6.  **Save User:** Click the `Save` button to create the user.

## 3. Ordering and Setting Up Network Ports

This section outlines the process for creating a Port within your customer Portal network. Your organization's Port serves as the physical connection point between your internal network and the insidepacket network. A Port must be deployed wherever you wish to route traffic.

1.  **Log in to the NaaS Portal.**
2.  **Navigate to Build Your Network:** From the left-hand side menu, select `Build Your Network`.
3.  **Choose Ports:** On the left side of the `Build Your Network` section, choose `Ports`.
4.  **Order Ports:** Click on the `+Order Ports` button.
5.  **Fill Port Details:**
    * **Connection Type:** Select the type of connection (e.g., Data Center).
    * **Country:** Choose the country.
    * **City:** Select the city.
    * **Building Name/Address:** Enter the building name or address.
    * **Choose the BW (Bandwidth):** Select the desired bandwidth (e.g., 10 Gbps).
6.  **Place Order:** Click the `Order` button to place the request.

**Note:** After ordering the port, its status will be marked as `Pending`, awaiting approval from the Administrator.

### Viewing Order Log

You can track the status of your port orders and other actions:

1.  **Navigate to the Order Log tab:** This is located on the left side of the page.
2.  **Review Records:** Here, you will find a detailed record of all actions performed, including:
    * Ordering new ports
    * Deleting ports
    * Enabling services (e.g., Network Observability, Firewall)
    * Ordering public IPs
    * Changing packages
3.  **Filter Options:** Options are available to filter the Order log by category or view all order actions.

### Port Provisioning and Availability

* **Provisioning:** After placing the order, the port will remain in `Pending` status until the Admin begins provisioning. This process typically takes a few hours.
* **Availability:** Once provisioning is complete, the port will become `Active` and ready for use. Connections can then be established on these ports.


