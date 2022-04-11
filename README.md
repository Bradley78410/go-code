package main

import "fmt"

func main() {
	message := "Hello World !"

	// Pointer to string
	var pMessage *string

	// pMessage points to addr of message
	pMessage = &message
	fmt.Println("Message = ", *pMessage)
	fmt.Println("Message Address = ", pMessage)
}
