# GDG SIL - Build Webapps with React 2.0

## Steps to Get Started:

1. **Fork this repository**  
   Click the "Fork" button on the top-right of the repo page.

2. **Open GitHub Codespaces**  
   In the URL of your forked repo, change `.com` to `.dev`  
   For example:  
   ```
   https://github.com/your-username/repo-name  
   ↓  
   https://github.dev/your-username/repo-name
   ```

3. **Create a New Terminal in Codespaces**  
   Once GitHub Codespaces loads:
   - Click on "Continue in GitHub Codespaces"
   - Choose the **first option** under **CPU Config**

4. **Create a New Branch with Your Name**  
   In the terminal, run:
   ```
   git switch -c <your_name>
   ```

5. **Add Your Details to the `attendees.csv` File**  
   Navigate to the `attendees.csv` file and add your details in the given format on a **new line**:
   ```
   ID, Name, Department, Batch
   ```
   Example:
   ```
   2300030001, Maname, CSE, Y23
   ```

6. **Create a New React App Using Vite (with TypeScript + SWC)**  
   In the terminal, run:
   ```
   npm create vite@latest
   ```
   - Enter your **ID number** as the project name
   - Choose:
     - Framework: **React**
     - Variant: **TypeScript + SWC**

7. **Navigate to the Project Directory & Run the App**  
   Replace `<id_number>` with your actual ID:
   ```
   cd <id_number>
   npm install
   npm run dev
   ```

8. **You're all set!**  
   Wait for the actual session to begin 🚀