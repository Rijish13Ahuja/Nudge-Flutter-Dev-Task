# Nudge-Flutter-Dev-Task
he app has three pages: Home, About, and Contact. The Home page is the landing page and has a component that toggles between a Launcher and a Banner. The Contact page only displays the Banner component, and the About page displays a simple text message.

Getting Started
To use this code, you need to have Flutter installed on your system. You can download it from here.
Clone this repository to your local machine.
Open the project in your preferred IDE or editor.
Run the code using a simulator or physical device.
File Structure
The code consists of a single file, main.dart. It contains the following components:

MyApp
This component is a stateless widget that creates the MaterialApp object that defines the app's navigation structure. It defines three routes: Home, Contact, and About.

HomePage
This component is a StatefulWidget that displays the Launcher/Banner component and a button that toggles between them.

ContactPage
This component is a StatelessWidget that displays the Banner component only.

AboutPage
This component is a StatelessWidget that displays a simple text message.

RootComponent
This component is a StatelessWidget that decides which component to show based on a boolean value.

Launcher
This component is a StatelessWidget that displays a blue container with the text "Launcher" and a tap listener that shows a modal bottom sheet.

Banner
This component is a StatelessWidget that displays a green container with the text "Banner" and a tap listener that navigates to the About page.
