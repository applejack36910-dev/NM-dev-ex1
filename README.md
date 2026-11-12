# NM-dev-ex1

Step 1: Import your Spring Boot project
1. Open Eclipse.
2. Go to File → Import.
3. Expand Maven.
4. Select Existing Maven Projects.
5. Click Next.
6. Under Root Directory, click Browse.
7. Select the extracted Spring Initializr project folder (the folder containing pom.xml).
8. Eclipse should automatically detect your project.
9. Click Finish.
Step 2: Verify the project
In Package Explorer, you should see something like:
college-erp
 ├── src/main/java
 ├── src/main/resources
 ├── src/test/java
 ├── JRE System Library
 ├── Maven Dependencies
 └── pom.xml

Wait until Maven finishes downloading dependencies.
Step 3: Enable Git using EGit
1. Right-click your college-erp project.
2. Select Team → Share Project.
3. Select Git.
4. Click Next.
5. Select your project.
6. Click Create Repository if prompted.
7. Click Finish.
Your project is now a local Git repository.
Step 4: Create a GitHub repository
Go to GitHub.
1. Create a new repository named college-erp.
2. Choose Public or Private.
3. Don't initialize it with a README.
4. Click Create Repository.
5. Copy the HTTPS URL.
Step 5: Connect GitHub to Eclipse
In Eclipse:
1. Right-click the project.
2. Select Team → Remote → Push.
3. Enter your GitHub repository URL.
4. Enter your GitHub username and Personal Access Token if prompted.
5. Configure the branch:
   - Source: refs/heads/main
   - Destination: refs/heads/main
6. Click Next → Finish.
Step 6: Your daily Git operations
Operation	Eclipse menu
Pull	Right-click → Team → Pull
Commit	Right-click → Team → Commit
Push	Right-click → Team → Push to Upstream
Fetch	Right-click → Team → Fetch
View history	Right-click → Team → Show in History


Your everyday workflow:

Pull → Code → Commit → Push
