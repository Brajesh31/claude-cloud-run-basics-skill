# Cloud Run Basics

A practical skill for deploying and managing services, jobs, and worker pools on Google Cloud Run.

## Capabilities

- Deploy container images or applications from source.
- Configure Cloud Run services and HTTP endpoints.
- Run jobs for scheduled, batch, or event-triggered workloads.
- Operate worker pools for continuously running background consumers.
- Configure IAM, service identities, environment variables, scaling, and logs.
- Troubleshoot deployment and runtime behavior.

## Prerequisites

You need a Google Cloud project, the relevant APIs enabled, and appropriate IAM permissions. Follow the role and API requirements in `SKILL.md`.

## Important deployment detail

Cloud Run containers must listen on `0.0.0.0` and use the injected `PORT` environment variable. Review authentication and ingress settings before exposing a service publicly.

## Usage

Use this skill when deploying or operating workloads on Cloud Run. Consult the detailed instructions in `SKILL.md` and verify the deployed service, job, or worker pool using logs and health checks.
