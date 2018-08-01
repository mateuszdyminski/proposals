### Title:
Zero-Downtime deployments of Java applications with Kubernetes

### Tags:
Kubernetes, Java, Deployment, Software Craftsmanship, Cloud 

### Short Abstract:
#### EN:
Developers, Ops teams, and end users have always been nervous about deployments because maintenance windows had a tendency to expand, causing unwanted downtime. Teams of ops engineers used to handle deployment efforts by-hand or via scripting - this process might could take hours, if not all night. The revolutionary Kubernetes deployment system, on the other hand, has built-in features that automate this operations effort, where end-user wan't be able to notice that the application version has changed in meantime. The presentation shows the technics which we as developers might use to make the deployment smooth and invisible for our users. Of course the work needs to be done on both sides: development and operations to achieve our Zero-Downtime goal - so presentation would be rather code and Kubernetes examples heavy than the plain theory.
#### PL:
Prezentacja ma na celu pokazanie technik deploymentu na platformie Kubernetes dzięki, którym końcowy użytkownik nie zauważy, ze wersja, której używa właśnie się zmieniła. Techniki te to: Rolling release, Blue-Green deployment oraz Canary deployment. Każdy z przedstawionych deploymentów będzie miał część teoretyczną jak i praktyczną, bo prezentacja bez live dema to nie prezentacja dla programisty. Co więcej aplikacja, którą będziemy releasować w nowej wersji to prosty serwis napisany w Springu. Na deser pokaże co to jest Graceful Shutdown i jak poprawnie zaimplementować go w Springu. Przygotujcie się na mnóstwo dem oraz kodu!

### Level of knowledge required from the audience:
beginner/intermediate

### Project Repo
[Repository with Code and presentation](https://github.com/mateuszdyminski/zero)