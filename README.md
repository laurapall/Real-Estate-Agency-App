# Oracle Apex Project - Real Estate Agency Application

## Language
The project is implemented using Oracle Application Express (APEX).

## Project Description:

The "Agentie imobiliara" project is a web-based application developed using Oracle Application Express (APEX). It serves as a Real Estate Agency management system, allowing users to manage property information, agents, transactions, and generate various reports and charts related to the agency's activities.

## Application Pages:

1. **Adaugarea datelor (Data Entry):**
   - This page enables users to add new data to the system, including:
     - Adding new "judet" (county) records.
     - Adding new "localitate" (locality) records associated with their respective counties.
     - Adding property details with a procedure (stored in the database).
     - Adding new "agent" records to manage agency staff.

<br><br>

<img width="2048" alt="Screenshot 2023-07-16 at 18 57 49" src="https://github.com/laurapall/Real-Estate-Agency-App/assets/48211193/a46a32de-843e-41c9-a0f4-cc0e01e3a055">

<br><br>
     

2. **Modificarea datelor (Data Modification):**
   - This page allows users to modify existing data, including:
     - Updating "judet" and "localitate" information.
     - Editing property details (imobil).
     - Modifying agent details (agent).
     - Changing property types (tip imobil).
     - Associating agents with properties (imobil).
    
<br><br>

<img width="2048" alt="Screenshot 2023-07-16 at 18 58 09" src="https://github.com/laurapall/Real-Estate-Agency-App/assets/48211193/c02b81f0-086a-4599-9554-3af120f1e044">
  
<br><br>

3. **Informatii (Information):**
   - Master Detail page - stacked, side by side, drill down.
   - This page provides detailed information in a master-detail format.
   - Users can view data such as properties (imobil), agents, and transactions (tranzactii).
  
  <br><br>
  
<img width="2048" alt="Screenshot 2023-07-16 at 18 58 27" src="https://github.com/laurapall/Real-Estate-Agency-App/assets/48211193/ca0bf385-dac0-4424-b294-e9329c4804d1">

   <br><br>

4. **Rapoarte (Reports):**
   - This page offers various reports to assist in decision making, including:
     - A list of localities (localitatilor).
     - A list of agents (agentilor).
     - Transaction details based on selected properties (selectare imobil).
     - A chart representing agent performance based on sales.
    
         <br><br>
         
<img width="2048" alt="Screenshot 2023-07-16 at 18 59 02" src="https://github.com/laurapall/Real-Estate-Agency-App/assets/48211193/2898d33d-59e8-47e2-b66f-3b1b44c9a191">

       <br><br>

## Database Tables:

The application relies on the following database tables:

1. **P_Imobil:**
   - Columns: cod_imobil, marime, adresa_imobil, cod_localitate, cod_tip_imobil, cod_camere.

2. **P_Legaturi:**
   - Columns: cod_imobil, cod_agent, cod_tranzactie.

3. **P_Agenti:**
   - Columns: cod_agent, nume_agent, prenume_agent, telefon_agent, e-mail_agent.

4. **P_Tranzactii:**
   - Columns: cod_tranzactie, data_afisare_imobil, data_tranzactie, pret_listare, pret_tranzactie.

5. **P_localitate:**
   - Columns: cod_localitate, localitate, cod_judet.

6. **P_Tip_imobil:**
   - Columns: cod_tip_imobil, tip_imobil.

7. **P_Camere:**
   - Columns: cod_camere, nr_camere.

8. **P_judet:**
   - Columns: cod_judet, judet.
 
  <br><br>
  
<img width="2048" alt="Screenshot 2023-01-28 at 08 17 27" src="https://github.com/laurapall/Real-Estate-Agency-App/assets/48211193/719419fd-6d26-438a-90e6-acc97408be10">

  <br><br>
  
## Application Setup:

To set up the application in Oracle APEX, follow these steps:

1. Import the provided application file into Oracle APEX.

2. Create the required database tables using the provided table structure.

3. Define the necessary data entry forms and reports based on the mentioned pages and tables.

4. Configure the necessary relationships and constraints between tables for data integrity.

5. Implement the required PL/SQL procedures and functions for data manipulation.

## Usage Instructions:

Once the application is set up and running, users can perform the following tasks:

- Use the "Adaugarea datelor" page to add new records for counties, localities, properties, and agents.

- Utilize the "Modificarea datelor" page to modify existing data, including property details and agent information.

- Access the "Informatii" page to view master-detail information on properties, agents, and transactions.

- Generate various reports and charts using the "Rapoarte" page to gain insights into localities, agents, transactions, and agent performance.

## Additional Notes:

- Please ensure that you have the necessary permissions to access and modify the Oracle APEX application and database objects.

- Regularly back up the application and database to prevent data loss and facilitate recovery if needed.

## License

The "Agentie imobiliara" project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

<br><br>

**Thank you for using the "Agentie imobiliara" application! Should you have any further questions or encounter any issues, please feel free to reach out for assistance: [flaurapall@gmail.com].**

## Author

* [Pall Laura](https://github.com/laurapall)

