<!-- markdownlint-disable MD033 -->

# Introduction

Contigo Burrito is a project that aims to achieve real-time tracking of the UNMMS internal
transport bus (*or buses!*) to make students' lives easier, as well as:

- In-app notifications in the form of banners, popups and posts.g
- App versioning and forcing client updates.
- Real-time tracking of the bus location, status and device battery.
- Bus stops and route information, including the distance to the next stop.
- User sessions (for analytics) and authentication (for protected resources).
- Feature flags for both server and clients.
- Multimedia upload integration with [Cloudinary](https://cloudinary.com/).

The following document contains all the technical high-level documentation of the project,
including development setup, compilation, distribution, deployment, and other relevant
information.

## Components

The project is divided into four main components, each with its own repository:

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

## Support and Contact

Feel free to reach out to the team if you have any questions or need help with the project:

- Paolo Flores [@paoloose](https://github.com/paoloose),
[pflores.fisi22@gmail.com](mailto:pflores.fisi22@gmail.com)

- Luis Calle [@luedu1103](https://github.com/luedu1103)

- Sebastian Rojas [@SebastianRojas6](https://github.com/SebastianRojas6)
