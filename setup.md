# Setup of the App

This setup is typically performed by an IT specialist familiar with terminal operations and technical procedures; this section is not intended for medical professionals.

1. Navigate to the `medseg_main` folder.
2. Run the `setup.py` script with the following command:

```bash
   cd PATH_TO_medseg_main
   python3 setup.py

```

Upon execution:

- The server's IP address will be added to the parameters.json and config.js files for use in other functionalities.
- The various Docker images will be loaded onto the new machine.
