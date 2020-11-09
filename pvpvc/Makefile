all:
	-kubectl apply -f pv.yaml
	-kubectl apply -f pv2.yaml
	-kubectl apply -f pv3.yaml
	-kubectl apply -f pvc.yaml
	-kubectl apply -f pvc2.yaml
	-kubectl apply -f pvc3.yaml
	-kubectl apply -f pod.yaml

clean:
	-kubectl delete -f pod.yaml
	-kubectl delete -f pvc.yaml
	-kubectl delete -f pvc2.yaml
	-kubectl delete -f pvc3.yaml
	-kubectl delete -f pv.yaml
	-kubectl delete -f pv2.yaml
	-kubectl delete -f pv3.yaml

pv:
	-kubectl apply -f pv.yaml
	-kubectl apply -f pv2.yaml
	-kubectl apply -f pv3.yaml

rmpv:
	-kubectl delete -f pv.yaml
	-kubectl delete -f pv2.yaml
	-kubectl delete -f pv3.yaml

rmpvc:
	-kubectl delete -f pvc.yaml
	-kubectl delete -f pvc2.yaml
	-kubectl delete -f pvc3.yaml
	-kubectl delete -f pvc4.yaml
