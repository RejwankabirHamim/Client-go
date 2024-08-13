#Command:

go run main.go

kubectl port-forward svc/bookservice 9090:4000

Now go to http://localhost:9090/books
