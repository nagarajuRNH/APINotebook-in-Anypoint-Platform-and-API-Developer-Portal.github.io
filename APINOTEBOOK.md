# API Notebook in Anypoint Platform and API Developer Portal

> The API Notebook can create a client for an API when you specify the URL for the API&#39;s RAML spec. With that client you can send authenticated requests to the API and receive live data in return.

- Here user need not to install any thing in his local we just needed to share the URL

- URL of the API in Developer Portal.

## Creating a Notebook:

- Login to Anypoint Platform

- Create RML in Design Centre

![DesignCenterImage](images/Picture1.png)

- Click on publish to Exchange

##

![Exchange](images/Picture2.png)

- Go to Exchange there you can see the API get published

 ![Publish-to-Exhange](images/Picture3.png)

- •	Now open the published API and Click on Edit in the Top Right corner

 ![API-Notebook](images/Picture4.png)

- Now Click on API Notebook a snippet gets Generated

 ![API-Get-Published](images/Picture5.png)

- Repeat the same by clicking on the API Notebook and Click on  Save Draft

 ![API-Notebook](images/Picture13.png)

- Now Click on Publish  so the API Notebook get created

 ![Genereate-Snippet-In-API-Notebook](images/Picture6.png)

- Now Play the first snippet so the client gets created.
- After the client created play the Next Snippet so can see the  Mock response from Response

 ![SaveDraft-API-Notebook](images/Picture7.png)

- Now Publish the API to Developer Portal.
- In the top right corner click on share and then select public and select the API  version and click on Save

 ![Click-on-Publish-API-Notebook](images/Picture8.png)



- Now go back to Exchange and Click on Public Portal in the left edge.

 ![Run-Snippet-API-Notebook](images/Picture9.png)

- Now the API can be seen in the Developer Portal Open the API you can see the API Published with API Notebook the Only thing you need to do is share the URL of the API in the Developer Portal so User can see the Mock Response.

 ![DesignCenterImage](images/Picture10.png)

- If the API is with Client id Enforcement, we need to pass the client\_id and client\_secret as Headers as below.

 ![DesignCenterImage](images/Picture11.png)

- If you need to pass the Post method with Parameters

![DesignCenterImage](images/Picture12.png)

 
