<!-- markdownlint-disable MD033 -->

# Overview

Here is a brief overview of the Contigo Burrito project and how its components
interact with each other. For more detailed information, refer to the specific
documentation of each component.

## Components

The project is divided into four main components, each with its own repository:s

<table>
  <thead>
    <tr>
      <th>Repository</th>
      <th>Description</th>
      <th>Technologies</th>
    </tr>
  </thead>
<tbody>
  <tr>
    <td><a href="https://github.com/burrito-project/burrito-app">burrito-app</a></td>
    <td>The app that students use to check the bus status.</td>
    <td>Flutter, Riverpod, Google Maps</td>
  </tr>
  <tr>
    <td><a href="https://github.com/burrito-project/burrito-server">burrito-server</a></td>
    <td>REST API server responsible</td>
    <td>Rust, Rocket</td>
  </tr>
  <tr>
    <td><a href="https://github.com/burrito-project/burrito-driver">burrito-driver</a></td>
    <td>Bus driver app that sends the location data.</td>
    <td>Flutter, Geolocator</td>
  </tr>
  <tr>
    <td><a href="https://github.com/burrito-project/burrito-dashboard">burrito-dashboard</a></td>
    <td>Admin dashboard to interact with the system.</td>
    <td>Vite, React</td>
  </tr>
</tbody>
</table>

Note that these are private repositores, so you may need to request access to them.

## Architecture

The project follows a client-server architecture, where the server and driver are responsible for
managing the data and the clients are responsible for displaying it.

![Project architecture](./assets/architecture_diagram.png)
