
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle Simulation </h1>
  <p>
This tutorial outlines the help desk ticket lifecycle. It simulates the intake/creation of a ticket to the resolution of the ticket. osTicket will be used for this simulation.
</p>
  <br>
  <h2>Prerequisites</h2>
  <p>-Install osTicket www.github.com/anakamura1/osticket-prereqs</p>
  <p>-Configure osTicket www.github.com/anakamura1/osticket-post-install-config</p>

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- osTicket

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Ticket Lifecycle Objectives</h2>

- 
- Item 2
- Item 3
- Item 4
- Item 5

<h2>Configuration Steps</h2>
<table>
  <tr>
    <td>
<img width="950" alt="Screenshot 2025-01-09 at 12 53 41 PM" src="https://github.com/user-attachments/assets/94d36b63-4ceb-4bd9-8dd5-05986c00150b" />
    </td>
    <td>
<img width="841" alt="Screenshot 2025-01-09 at 12 55 04 PM" src="https://github.com/user-attachments/assets/67b24e11-d417-406b-8554-5a04ef59f884" />
    </td>
  </tr>
</table>

</p>
<p>
  Begin by entering http://localhost/osTicket into the browser. This will bring us to the end user ticket creation page. Here we can submit a ticket as Karen. After the ticket is submitted, log in at http://localhost/osTicket/scp/login.php as agent John Doe. 
</p>

<table>
  <tr>
    <td>
            <img  width="800" alt="Screenshot 2025-01-09 at 1 17 01 PM" src="https://github.com/user-attachments/assets/724fa26e-a1ff-4acf-bce1-7b231e968f73" />
    </td>
    <td>
          <img width="650" alt="Screenshot 2025-01-09 at 1 05 07 PM" src="https://github.com/user-attachments/assets/317a97d8-3241-44cd-9572-962263bf8fe0" />
    </td>
  </tr>
</table>

<p>Karen has submitted a ticket regarding users not being able to use the online banking platform. We can view this ticket as an agent.</p>
<P>We can assign the ticket to John as well as the mobile banking team we created. Take note of the SLA and priority. These can be modified if needed when we find out more about the ticket. </P>
<br>



<img height="80%" width="80%"  alt="Screenshot 2025-01-09 at 1 07 38 PM" src="https://github.com/user-attachments/assets/2250bfde-a0cf-4fbf-a9c4-3cc86bebf5a2" />

<p>Now as an agent we can acknowledge Karen's ticket and begin "working" it to completion.</p>

<br>

<img height="80%" width="80%" alt="Screenshot 2025-01-09 at 1 16 18 PM" src="https://github.com/user-attachments/assets/9e6cd9a8-1c35-48c8-9b0f-bcb8da1cf11c" />
<p>
  osTicket keeps track of all correspondance between the agents and users to keep track of progress.
</p>
<br>

<img height="80%" width="80%" alt="Screenshot 2025-01-09 at 1 17 01 PM" src="https://github.com/user-attachments/assets/724fa26e-a1ff-4acf-bce1-7b231e968f73" />

<p>Once we "work" this ticket to resolution, we can scroll up to the top and change the status to "resolved". In the overview page under the tickets tab, we can view closed tickets. These are tickets that have been resolved and closed. </p>

<br>
<img height="80%" width="80%" alt="Screenshot 2025-01-09 at 1 23 53 PM" src="https://github.com/user-attachments/assets/0ae0ed02-5aa9-4966-983b-954a49577862" />
<p>
To simulate ticket intake via phone or email, we can navigate to tickets as an agent and create a new ticket. The new ticket can be created based on the nature of the issue being reported.
</p>

<br>

<table>
  <tr>
    <td>
      <img  width="850" alt="Screenshot 2025-01-09 at 1 44 43 PM" src="https://github.com/user-attachments/assets/81bc8b2f-233a-4d7f-b255-dba8ac12c526" />
    </td>
    <td>
      <img  width="650" alt="Screenshot 2025-01-09 at 1 43 35 PM" src="https://github.com/user-attachments/assets/0d68afe8-eddd-4b70-bc83-9e3b357ceb72" />
    </td>
  </tr>
</table>

<p>We can submit replies to the ticket and "work" the ticket to resolution. As we learn more information about the ticket we can change various elements about the ticket like the SLA.
Instead of the entire department not being able to use Adobe we realize it is just 2 users, this prompts a change in the SLA. 
</p>

**There are lots of other things that can be done within osTicket so feel free to explore around to build more intuition with osTicket**

**This conlcudes the Ticket Lifecycle lab!**
