FROM golang:1.17.3-alpine3.14

WORKDIR /app

COPY . .

RUN go mod download

RUN go build -o server .

EXPOSE 4001

CMD ["./server"]

#Backend run (no funciono con multistage)

#FROM alpine:3.14

#WORKDIR /app

#ENV PORT=4001
#EXPOSE 4001

#COPY --from=build /app/server .

#CMD ["./server"]