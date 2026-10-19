# Access Control (ACL)

# RBAC - CSO Online 

**Role Based Access Control** is a security system that assigns permissions to users based on their roles within an organization. It is important because it protects sensitive information, prevents unauthorized access, and makes managing user permissions easier. For implementation, I would first identify the different user roles and determine which permissions each role needs. Then, I would implement authentication to verify users and authorization middleware to check their roles before allowing access to protected routes. In simple terms, I would compare RBAC to employees working in a store. A cashier can process purchases, a manager can approve refunds, and an administrator can manage employee accounts. Everyone has different responsibilities and access based on their position. RBAC works the same way in computer systems.

# Role/Permission Hierarchy: 

- **Admin**: Full access and management of users.
- **Editor**: Creates, updates but cannot manage users.
- **User**: View content and manage profile. 

## Authorization vs. Authentication

Authorization determines what a user is allowed to access or do after their identity has been verified. For example, a user may successfully log into a website but might not have permission to access administrator settings.

# Primary rules for RBAC
1. Role Assignment
2. Role Authorization
3. Permission Authorization

## RBAC Tutorial (Video)

1. **What are access rights associated with? The user or the role? Explain.**
- Access rights are associated with the role, not directly with the individual user. Users are assigned roles, and those roles determine what actions they can perform within a system.
2. **Access rights, or authorization, are activated after a user successfully does what?**
- After a user successfully completes authentication, such as logging in with a valid username and password, the system can check their role and determine which resources and actions they are authorized to access.
3. **Explain how RBAC might benefit a business.**
- RBAC helps businesses keep their information secure while making it easier to manage employee access. It reduces the risk of unauthorized activity, keeps responsibilities organized, and saves time when assigning permissions to employees.