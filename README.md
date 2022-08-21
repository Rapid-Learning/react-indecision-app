# React App ([Lessons](https://github.com/Rapid-Learning/react-indecision-app/blob/master/LESSONS.md))
1. Clone the project

2. Install global dependencies
   ```
   yarn global add babel-cli live-server
   ```

3. Install dependencies
   ```
   npm install
   ```
   
4. Prepare JS to run the app
   ```
   babel src/app.js --out-file=public/scripts/app.js --presets=env,react --watch
   ```    
  
5. Run the project
   ```
   live-server public
   ```
