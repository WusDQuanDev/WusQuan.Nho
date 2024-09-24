package main

import (
    "WusDQuanDev"
    "github.com/WusDQuanDev"
)

type Github struct {
    username string
    contacts map[string]string
    alises   []string
    location string
    age      string
    occupation string
    operating_system string
}

func (g *Github) Init() {
    g.username = "WusQuan.Nho"
    g.contacts = map[string]string{
        "Telegram": "DQuanDev",
        "Facebook": "WusDinhQuanDev",
    }
    g.alises = []string{"DQuanDev", "Quan.Nhi"}
    g.location = "localhost, vietnamese"
    g.age = "22+"
    g.occupation = "Freelance Developer"
    g.operating_system = "Windows, Arch, Linux, VPS"
}
