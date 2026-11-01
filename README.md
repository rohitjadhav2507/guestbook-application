# IBM Cloud & Kubernetes Guestbook Final Project Submissions

All completed deliverables for the 10 graded tasks:

| Question | File Name | Points | Description |
|---|---|---|---|
| **Question 1** | `Dockerfile` | 1 pt | Completed Dockerfile with multi-stage build, `COPY`, and `EXPOSE 3000` |
| **Question 2** | `submissions/crimages` | 1 pt | `ibmcloud cr images` terminal output showing `v1` image in IBM Cloud Container Registry |
| **Question 3** | `submissions/app` | 1 pt | `index.html` displaying "Guestbook - v1" in `<title>` and `<h1>` |
| **Question 4** | `submissions/hpa` | 1 pt | Initial `kubectl get hpa guestbook` output |
| **Question 5** | `submissions/hpa2` | 2 pts | Scaled `kubectl get hpa guestbook` output showing autoscaled replica count |
| **Question 6** | `submissions/upguestbook` | 2 pts | `docker push` terminal output for updated guestbook image with digest |
| **Question 7** | `submissions/deployment` | 1 pt | `kubectl apply -f deployment.yml` output (`deployment.apps/guestbook configured`) |
| **Question 8** | `submissions/up-app` | 2 pts | Updated `index.html` displaying "Guestbook - v2" in `<title>` and `<h1>` |
| **Question 9** | `submissions/rev` | 2 pts | `kubectl rollout history` showing CPU revision details |
| **Question 10** | `submissions/rs` | 2 pts | `kubectl get rs` showing 2 ReplicaSets present after deployment rollback |
