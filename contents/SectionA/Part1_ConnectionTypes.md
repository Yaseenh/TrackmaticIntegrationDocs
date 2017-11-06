<h1 style="text-align: center;">
<span style="color:grey">Section A</span>
</h1>

# <span style="color:grey">Part 1</span>

## <span style="color:grey">SQL</span>
__Polling Listener__

This is installed as a service on the client’s local server or machine. It listens to a 'Trackmatic-Changes' table placed within the client’s database. This table records all the changes been made to the relevant client’s tables needed to use Trackmatic’ s services. These changes in relation to the tables are then traced, picked up and updated in Trackmatic.

## ![Adding pic](../../Images/pollingListener.png)

## <span style="color:grey">XML or JSON</span>
__Web Service Request To Azure__

The client presents the required data to our web service in XML or JSON. Upon receiving it, it is then mapped and uploaded into Trackmatic.

## ![Adding pic](../../Images/webServiceListener.png)

## <span style="color:grey">CSV</span>
__SFTP/FTP__

The client drops an excel extract (CSV) to the SFTP/FTP server containing all the relevant data to use Trackmatic services. The integration agent polls the directory of the SFTP/FTP for the file. If an extract is picked up, it is then read in and uploaded into Trackmatic. The client can choose to use their own SFTP/FTP server (preferable) or Trackmatic’ s SFTP/FTP server.

## ![Adding pic](../../Images/sftp_ftpListener.png)

__Email Listener__

The client emails an excel extract (CSV) containing all the relevant data to use Trackmatic’ s services to an email address provided by Trackmatic. The integration agent which is running on Trackmatic’ s server will then pick up this email. If an extract is picked up within the email, it will then be read in and uploaded into Trackmatic.

## ![Adding pic](../../Images/emailListener.png)

__Flat file Listener__

Very much like SFTP/FTP, the client drops an excel extract (CSV) containing all the relevant data to use Trackmatic’ s services onto a local directory in Trackmatic’  s server. The integration agent which is running on Trackmatic’ s server will poll the directory for the file. If an extract is picked up, it is then read in and uploaded into Trackmatic.

## ![Adding pic](../../Images/flatFileListener.png)