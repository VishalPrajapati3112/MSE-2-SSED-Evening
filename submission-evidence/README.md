# Submission evidence status

Thirteen genuine screenshots are included:

- `01-frontend-build.png` and `02-backend-build.png` - fresh Docker Compose image builds and local image inspection.
- `03-compose-services.png` - four image-deployment services running and healthy.
- `04-docker-network.png` - Compose bridge network name, driver, scope, and connected container count.
- `05-postgres-health.png`, `06-redis-health.png`, and `07-backend-health.png` - live container health and backend health route.
- `08-postgres-persistence.png` - a fresh sentinel survived PostgreSQL container removal and recreation; the named volume was retained.
- `09-redis-restart.png` - Redis restarted, became healthy, and returned `PONG`.
- `10-dockerhub-frontend.png` and `11-dockerhub-backend.png` - public Docker Hub tags.
- `12-image-deployment.png` - image pull, health-gated deployment, four healthy services, and both health routes.
- `13-application-browser.png` - TaskFlow served by the published-image deployment.

All terminal captures show live command output from this audit. They were captured from the full desktop terminal view without editing or adding output to the images.

Still unavailable (not fabricated):

- `14-github-actions.png` - NOT VERIFIED; one dispatch attempt could not be completed with the authenticated access available in this environment, so no run exists to capture.
- `15-github-repository.png` - the attempted page capture did not render repository contents.
- `16-pull-request.png` - PR creation was rejected by the GitHub integration with HTTP 403 (`Resource not accessible by integration`), so no PR exists.
- `17-instructor-ci.png` - pending creation of the PR; no instructor checks exist yet.

Repository: https://github.com/VishalPrajapati3112/MSE-2-SSED-Evening
Workflow: https://github.com/VishalPrajapati3112/MSE-2-SSED-Evening/actions/workflows/cd.yml (NOT VERIFIED; no run URL)
Pull Request: NOT CREATED; the GitHub integration rejected the request with HTTP 403.

Regenerate the PDF with `python scripts/generate_submission_pdf.py`; matching numbered PNGs are embedded automatically.
