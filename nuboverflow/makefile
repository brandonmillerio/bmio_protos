build:
	protoc --go-grpc_out=. --go-grpc_opt=paths=source_relative user/**/*.proto
	cp user/**/*grpc.pb.go user/**/go/*grpc.pb.go
	mv user/v1/*grpc.pb.go ../../go_projects/nuboverflow_users/internal/user/