<html xmlns="http://www.w3.org/1999/xhtml">
<head>
    <title>SAP (JCO) Knowledge Sensor Pack</title>
    <meta http-equiv="Content-Type" content="text/html; charset=UTF-8"/>
    <meta http-equiv="X-UA-Compatible" content="IE=EmulateIE8" />
    <meta content="Scroll Wiki Publisher" name="generator"/>
    <link type="text/css" rel="stylesheet" href="css/blueprint/liquid.css" media="screen, projection"/>
    <link type="text/css" rel="stylesheet" href="css/blueprint/print.css" media="print"/>
    <link type="text/css" rel="stylesheet" href="css/content-style.css" media="screen, projection, print"/>
    <link type="text/css" rel="stylesheet" href="css/screen.css" media="screen, projection"/>
    <link type="text/css" rel="stylesheet" href="css/print.css" media="print"/>
</head>
<body>
                <h1>SAP (JCO) Knowledge Sensor Pack</h1>
    <div class="section-2"  id="4358224_SAP%28JCO%29KnowledgeSensorPack-Overview"  >
        <h2>Overview</h2>
    <div class="tablewrap">
        <table>
<thead class=" "></thead><tfoot class=" "></tfoot><tbody class=" ">    <tr>
            <td rowspan="1" colspan="1">
        <p>
Name    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
<strong class=" ">SAP (JCO) Knowledge Sensor Pack</strong>    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Description    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
This Knowledge Sensor Pack can be used to help quantify and diagnose performance issues related to usage of a JCO/ABAP calls from within SAP.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Version    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
1.1    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
dynaTrace Diagnostics Version    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
3.5 and higher    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Author    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
dynaTrace software    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
License    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
<a href="attachments_5275722_2_dynaTraceBSD.txt">dynaTrace BSD</a>    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Support    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
<a href="https://community/display/DL/Support+Levels#SupportLevels-Community">Community</a>    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Download    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
<a href="attachments_77660207_1_com.sap.mpw.jco.Remoting.SAP_Java_Connector.dtcs">com.sap.mpw.jco.Remoting.SAP_Java_Connector.dtcs</a>    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Applicable Version(s)    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
SAP JCO v2.1.7    </p>
            </td>
        </tr>
</tbody>        </table>
            </div>
    </div>
    <div class="section-2"  id="4358224_SAP%28JCO%29KnowledgeSensorPack-Installation"  >
        <h2>Installation</h2>
    <div class="confbox panel">
    <ol class=" "><li class=" ">    <p>
Save the attached file locally to the computer where the dynaTrace Diagnostics Client is installed.    </p>
</li><li class=" ">    <p>
In the dynaTrace Client, choose <i class=" ">Setting &rArr; dynaTrace Server Settings</i>    </p>
</li><li class=" ">    <p>
Click on &quot;Sensor Packs&quot;.    </p>
</li><li class=" ">    <p>
Click on the &quot;Import...&quot; button.    </p>
</li><li class=" ">    <p>
Select &quot;Custom Sensor Type (*.dtcs)&quot; in the &quot;Files of type&quot; dropdown.    </p>
</li><li class=" ">    <p>
Navigate to the directory where you extracted the .dtcs file and click &quot;Open&quot;.    </p>
</li></ol>    </div>
    <p>
You can confirm successful import by observing the &quot;Spring Sensor&quot; Sensor Pack in the Sensor Packs Panel. This Knowlege Sensor Pack is now <i class=" ">Placed</i> and <i class=" ">Active</i> within all System Profiles on this dynaTrace Server.    </p>
    <p>
Note:    </p>
    <p>
There is no visibility into the internals of ABAP calls, however by monitoring the JCO calls, the cost of calls from Java into ABAP can be measured and provide visibility into which ABAP calls are potentially causing problems.    </p>
    <p>
Note: This Knowledge Sensor Pack has been updated to handle SAP JCO v2.1.7.  This involved adding support for the class com.sap.mw.jco.JCO$Client.  Prior, the only class which was covered was com.sap.mw.jco.Client.  Same methods are used on both classes.    </p>
    </div>
            </div>
        </div>
        <div class="footer">
        </div>
    </div>
</body>
</html>
