# Industrial-IoT-Sandbox
Industrial-IoT-Sandbox

Excalidraw Diagram
<img width="2552" height="143" alt="Diagram" src="https://github.com/user-attachments/assets/ac8109be-f712-4149-b23f-35473b2b5985" />


"Lessons From The Field":
Node ID Mapping: "Used UA Expert to resolve the exact Namespace (ns) and String (s) identifiers, as CODESYS path strings can be complex."
Security Policies: "Managed 'Anonymous Login' vs. 'Encrypted' endpoints. Navigated the CODESYS Runtime Security Policy to allow initial handshaking."
Polling vs. Subscribing: "Implemented OPC UA Subscription mode in Node-RED to reduce network overhead compared to constant polling."

Codesys Source(Logic & Variables): https://docs.factoryio.com/tutorials/codesys/setting-up/codesys-opc-ua-sp17/#creating-the-project

Prerequisites: List CODESYS V3.5, Node.js, and UA Expert.
Installation: Copy the JSON, Make sure you have the JSON code copied to your clipboard (it usually starts with [ and ends with ]).Open the Menu: In your Node-RED editor, click the "hamburger" menu (three horizontal lines) in the top-right corner.Select Import: Click on Import.Paste the Code: Paste your JSON into the text area that appears.Confirm: Click the red Import button.Place and Deploy: Click anywhere on your workspace to drop the nodes, then hit the red Deploy button at the top right to make them live.

Video Explaining:
https://github.com/user-attachments/assets/4b8162aa-adbb-45a4-94c1-611082898ab6
