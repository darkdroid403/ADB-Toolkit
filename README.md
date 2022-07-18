# ADB-Toolkit
ADB Client tool for Windows

Source code: https://dl.google.com/android/repository/platform-tools-latest-windows.zip

Support Android 13

Some adb commands:
<p><strong>adb devices</strong><em>&nbsp;(lists connected devices)</em></p>
<hr />
<p><br /><strong>adb root</strong><span><strong>&nbsp;</strong><em>(restarts adbd with root permissions)</em></span></p>
<hr />
<p><br /><strong>adb start-server</strong><span>&nbsp;<em>(starts the adb server)</em></span></p>
<hr />
<p><br /><strong>adb kill-server</strong><span>&nbsp;<em>(kills the adb server)</em></span></p>
<hr />
<p><br /><strong>adb reboot</strong><span>&nbsp;<em>(reboots the device)</em></span></p>
<hr />
<p><br /><strong>adb devices -l</strong><span>&nbsp;<em>(list of devices by product/model)</em></span></p>
<hr />
<p><br /><strong>adb shell</strong><span>&nbsp;<em>(starts the backround terminal)</em></span></p>
<hr />
<p><br /><strong>exit</strong><span>&nbsp;<em>(exits the background terminal)</em></span></p>
<hr />
<p><br /><strong>adb help</strong><em>&nbsp;(list all commands)</em></p>
<hr />
<p><br /><span><strong>adb -s</strong> <strong>&lt;deviceName&gt; &lt;command&gt;</strong></span><span>&nbsp;<em>(redirect command to specific device)</em></span></p>
<hr />
<p><br /><strong>adb &ndash;d &lt;command&gt;</strong><em><strong>&nbsp;</strong>(directs command to only attached USB device)</em></p>
<hr />
<p><br /><strong>adb &ndash;e &lt;command&gt;</strong><span>&nbsp;<em>(directs command to only attached emulator)</em></span></p>


<table style="width: 100%;">
    <tbody>
        <tr>
            <td style="width: 29.4766%;"><strong>Command</strong><br></td>
            <td style="width: 70.5234%;"><span style="font-family: Courier New, courier;"><strong>pm</strong></span><br></td>
        </tr>
        <tr>
            <td style="width: 29.4766%;"><strong>About</strong></td>
            <td style="width: 70.5234%;"><em>Within an adb shell, you can issue commands with the <strong>package manager</strong> (<code translate="no">pm</code>) tool to perform actions and queries on app packages installed on the device&nbsp;</em><br></td>
        </tr>
        <tr>
            <td style="width: 29.4766%;"><strong>Options</strong></td>
            <td style="width: 70.5234%; background-color: rgb(239, 239, 239);"><span style="font-family: Courier New, courier;">pm list packages -f&nbsp;</span></td>
        </tr>
        <tr>
            <td style="width: 29.4766%;"><br></td>
            <td style="width: 70.5234%; background-color: rgb(239, 239, 239);"><span style='color: rgb(0, 0, 0); font-family: "Courier New", courier; font-size: medium; font-style: normal; font-variant-ligatures: normal; font-variant-caps: normal; font-weight: 400; letter-spacing: normal; orphans: 2; text-align: start; text-indent: 0px; text-transform: none; white-space: normal; widows: 2; word-spacing: 0px; -webkit-text-stroke-width: 0px; text-decoration-thickness: initial; text-decoration-style: initial; text-decoration-color: initial; float: none; display: inline !important;'>pm list packages -d</span><br></td>
        </tr>
        <tr>
            <td style="width: 29.4766%;"><br></td>
            <td style="width: 70.5234%; background-color: rgb(239, 239, 239);"><span style='color: rgb(0, 0, 0); font-family: "Courier New", courier; font-size: medium; font-style: normal; font-variant-ligatures: normal; font-variant-caps: normal; font-weight: 400; letter-spacing: normal; orphans: 2; text-align: start; text-indent: 0px; text-transform: none; white-space: normal; widows: 2; word-spacing: 0px; -webkit-text-stroke-width: 0px; text-decoration-thickness: initial; text-decoration-style: initial; text-decoration-color: initial; float: none; display: inline !important;'>pm list packages -e</span><br></td>
        </tr>
        <tr>
            <td style="width: 29.4766%;"><br></td>
            <td style="width: 70.5234%; background-color: rgb(239, 239, 239);"><span style='color: rgb(0, 0, 0); font-family: "Courier New", courier; font-size: medium; font-style: normal; font-variant-ligatures: normal; font-variant-caps: normal; font-weight: 400; letter-spacing: normal; orphans: 2; text-align: start; text-indent: 0px; text-transform: none; white-space: normal; widows: 2; word-spacing: 0px; -webkit-text-stroke-width: 0px; text-decoration-thickness: initial; text-decoration-style: initial; text-decoration-color: initial; float: none; display: inline !important;'>pm list packages -s</span><br></td>
        </tr>
        <tr>
            <td style="width: 29.4766%;"><br></td>
            <td style="width: 70.5234%; background-color: rgb(239, 239, 239);"><span style='color: rgb(0, 0, 0); font-family: "Courier New", courier; font-size: medium; font-style: normal; font-variant-ligatures: normal; font-variant-caps: normal; font-weight: 400; letter-spacing: normal; orphans: 2; text-align: start; text-indent: 0px; text-transform: none; white-space: normal; widows: 2; word-spacing: 0px; -webkit-text-stroke-width: 0px; text-decoration-thickness: initial; text-decoration-style: initial; text-decoration-color: initial; float: none; display: inline !important;'>pm list packages -3</span><br></td>
        </tr>
        <tr>
            <td style="width: 29.4766%;"><br></td>
            <td style="width: 70.5234%; background-color: rgb(239, 239, 239);"><span style='color: rgb(0, 0, 0); font-family: "Courier New", courier; font-size: medium; font-style: normal; font-variant-ligatures: normal; font-variant-caps: normal; font-weight: 400; letter-spacing: normal; orphans: 2; text-align: start; text-indent: 0px; text-transform: none; white-space: normal; widows: 2; word-spacing: 0px; -webkit-text-stroke-width: 0px; text-decoration-thickness: initial; text-decoration-style: initial; text-decoration-color: initial; float: none; display: inline !important;'>pm list packages -i</span><br></td>
        </tr>
        <tr>
            <td style="width: 29.4766%;"><br></td>
            <td style="width: 70.5234%; background-color: rgb(239, 239, 239);"><span style='color: rgb(0, 0, 0); font-family: "Courier New", courier; font-size: medium; font-style: normal; font-variant-ligatures: normal; font-variant-caps: normal; font-weight: 400; letter-spacing: normal; orphans: 2; text-align: start; text-indent: 0px; text-transform: none; white-space: normal; widows: 2; word-spacing: 0px; -webkit-text-stroke-width: 0px; text-decoration-thickness: initial; text-decoration-style: initial; text-decoration-color: initial; float: none; display: inline !important;'>pm list packages -u</span><br></td>
        </tr>
        <tr>
            <td style="width: 29.4766%;"><br></td>
            <td style="width: 70.5234%; background-color: rgb(239, 239, 239);"><span style='color: rgb(0, 0, 0); font-family: "Courier New", courier; font-size: medium; font-style: normal; font-variant-ligatures: normal; font-variant-caps: normal; font-weight: 400; letter-spacing: normal; orphans: 2; text-align: start; text-indent: 0px; text-transform: none; white-space: normal; widows: 2; word-spacing: 0px; -webkit-text-stroke-width: 0px; text-decoration-thickness: initial; text-decoration-style: initial; text-decoration-color: initial; float: none; display: inline !important;'>pm list packages --user</span></td>
        </tr>
    </tbody>
</table>
<p><br></p>
<table style="width: 100%;">
    <tbody>
        <tr>
            <td style="width: 100.0000%;"><strong>Syntax 1 <em>(from main adb)</em></strong></td>
        </tr>
        <tr>
            <td style="width: 100.0000%;">
                <pre translate="no"><span style="font-family: Courier New, courier;">adb shell pm<em>(</em><em>command)</em></span></pre>
            </td>
        </tr>
        <tr>
            <td style="width: 100.0000%;"><strong>Syntax 2 <em>(from shell)</em></strong></td>
        </tr>
        <tr>
            <td style="width: 100.0000%;"><br><span style="font-family: Courier New, courier;">pm list packages</span> <em>(</em><em>command)</em><br><br></td>
        </tr>
    </tbody>
</table>
<p><br></p>
<p><br></p>




