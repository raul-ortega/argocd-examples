# using alipne image (Dockerfile provided)

- image built from alpine:3.15.4

- avida 2.15 compiled from github.com/fortunalab/avida (commit ad7216c0349e44c922afad122ee24110b509edb7)

## launch from argocd template

kubectl apply -f https://raw.githubusercontent.com/raul-ortega/argocd-examples/main/05_avida.yaml


## launch from job template

kubectl apply -f https://raw.githubusercontent.com/raul-ortega/argocd-examples/main/avida/5/avida-job.yaml
