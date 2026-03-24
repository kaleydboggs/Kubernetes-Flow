# Kubernetes-Flow
Example Kubernetes Flow Structure

Kubernetes-Flow/

│
├── app/                        # Your OCR service code

  │   ├── app.py

  │   ├── requirements.txt

  │   └── Dockerfile
  │

├── k8s/                        # Kubernetes manifests

  │   ├── deployment.yaml

  │   ├── service.yaml

  │   └── job.yaml                 # optional batch OCR job

  │

├── scripts/                     # helper scripts

  │   ├── build.sh

  │   └── deploy.sh

  │

├── tests/                       # test OCR functionality
  │   └── test_app.py
  │
  ├── .gitignore
  └── README.md
