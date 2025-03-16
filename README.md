MINI HEALTH ASSISTANT

C-Programming Final Project

This project is developed as part of the BCT 2081 course by the following team members:
-Sudip Mahato(PUR081BCT087)
-Samundra Pariyar(PUR081BCT071)
-Rupak Subba(PUR081BCT063)
-Sayesh Dhakal(PUR081BCT080)

HOW TO USE:

### **Stepwise Process to Run and Use the Medical Diagnosis Program**  

#### **1. Compile and Run the Program**  
- Open a C compiler (e.g., GCC, Code::Blocks, or Dev-C++).  
- Save the program as `medical_diagnosis.c`.  
- Compile using the command:  
  ```
  gcc medical_diagnosis.c -o medical_diagnosis
  ```
- Run the program:  
  ```
  ./medical_diagnosis
  ```

#### **2. Enter the Current Date**  
- The program will prompt:  
  ```
  Enter today's date:
  ```
- Type the date (e.g., `11-03-2025`) and press **Enter**.

#### **3. Choose an Option from the Menu**  
- The program will display:  
  ```
  1. Enter new health data  
  2. Display previous health data  
  3. Need Consultation?  
  Choose the option:
  ```
- Enter the number corresponding to your choice.

#### **4. If You Choose Diagnosis (Option 1)**  
- The system displays symptom categories (Fever, Stomach Ache, High/Low Blood Pressure, Diabetes).  
- Select a category by entering the corresponding letter (e.g., `a` for Fever).  
- The program provides a diagnosis with health instructions.  
- It asks:  
  ```
  Do you want some medicine prescription? (y/n)
  ```
- Enter `y` for medicine recommendations or `n` to exit.

#### **5. If You Choose to View Past Health Data (Option 2)**  
- The program retrieves and displays the last recorded health data from `medical_report.txt`.

#### **6. If You Choose Doctor Consultation (Option 3)**  
- The system lists available doctors along with their experience, contact details, and hospitals.

#### **7. Exit the Program**  
- The program will terminate after displaying the requested information.  
- To restart, rerun the executable file (`./medical_diagnosis`).  

Let me know if you need further clarification! 🚀
