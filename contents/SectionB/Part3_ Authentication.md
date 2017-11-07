<h1>
<div style="text-align: center;">
    <span style="color:grey">
        Create Your Own Agent
    </span>
    <span style="float:right;color:grey">Section B</span>
</div>
</h1>
<h2>
<span style="float:right;color:grey">Part 1</span>
</h2>
<br /> 

### __Provide Access__

Upon completing the task of determining which Required Fields (Section A – Part 2) is needed, you will need to start creating your own integration.
In order to make use of our framework as well as push data to Trackmatic’ s API, you will require access to its libraries and authentication to its API:

1.	Trackmatic’ s libraries are accessible from NuGet use the following link: 
http://nuget.trackmatic.co.za/nuget
2.	 Packages you will need to make use of are:
     -	Trackmatic.Rest.Client
     -	Trackmatic.Api.Agent.Host
     -	Trackmatic.Api.Agent
     -	Trackmatic.Api.Agent.Polling  use if you are pulling data directly from a database. Trackmatic to provide Scripts if needed to use our triggers and table to listen to upon a change or insert. 

3.	Trackmatic will provide you with the following when authenticating to push data to our API:
    -	Client ID
    -	Integration Username
    -	Integration Password
    -	Api Address: https://rest.trackmatic.co.za/api/v1
