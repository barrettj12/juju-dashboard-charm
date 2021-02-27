# Juju Dashboard Charm

The charm to deploy the dashboard for [Juju](https://juju.is) and [JAAS](https://jaas.ai)

## Usage

This charm will be automatically deployed by your controller so you shouldn't
need to deploy it yourself manually.

## Developing

Create and activate a virtualenv with the development requirements:

    virtualenv -p python3 venv
    source venv/bin/activate
    pip install -r requirements-dev.txt

## Testing

The Python operator framework includes a very nice harness for testing
operator behaviour without full deployment. Just `run_tests`:

    ./run_tests
