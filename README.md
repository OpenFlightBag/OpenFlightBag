# OpenFlightBag

## Vision

OpenFlightBag intends to be the Electronic Flight Bag ([EFB]<https://en.wikipedia.org/wiki/Electronic_flight_bag>) solution for all kinds of users. No matter if it is used by a single Virtual/Sim Pilot or an Airline with one or multiple fleets and sub-fleets - even with a mixture of devices, like iPads / Windows Tablets / ...

The GPL license shall ensure, that no vendor lock-in happens. All the code, interfaces and data structures are vendor-independent and always publicly available. Third party providers, OEMs, software providers, etc. no longer need to take care about aviation-specific issues, like data availability or communication difficulties. Details will be available on the website in the future. Providers can focus on delivering the best tools, algorithms and UIs, while operators can choose the best available option for every use-case. For example, the Document Viewer can be provided by a different company, than the backoffice Content Management System. The electronic Flight Folder application is independent of the Dispatch Software. A flightplan that is stored in the OpenFlightBag, will be available for the charting application, the electronic Flight Folder, the Take-Off and Landing Performance Application, the Inflight-Weather application, the Airport familiarization application, the Reporting Application. All these applications will be aware of e.g. flightnumber, aircraft registration, departure airport, destination and alternate airports, coordinates of the planned route, ...

Besides the Open-Source concept, Scalability and Platform-Independency are key aspects for OpenFlightBag.  
Making use of the Qt-toolkit, shall ensure that OpenFlightBag can be used on many different hardware platforms with its operating systems.  
Depending on the requirements in terms of availabilty and ease-of-use, OpenFlightBag can be run on a single computer, with its core backend and also the frontend applications.
It can also be split in a backend and a frontend part, so that the core backend runs on one computer (e.g. a single board computer) and the frontend (the applications) runs on one or more tablets, that are connected to the backend (e.g. one Tablet per Pilot or one mounted EFB per Pilot for the frontend and one aircraft attached backend computer).
In a full-blown scenario, the backend should be covered by either a backup-backend computer or by using the frontend devices as backup backends.

No matter which setup (one computer for everything or multiple computers for backends and frontends) is used, this shall be transparent to the Pilots and as much as possible to the Frontend applications.
