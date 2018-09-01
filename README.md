# hyper-chain

Hyper-chain is a BlockChain platform that is useful for ***Scalability*** and ***Data Management***. this platform is offered as a ***Direct Installation*** and as a ***Docker Base***.

# project directory structure

```
├── README.md
├── blockchain
│   ├── channel
│   ├── block
│   ├── transaction
│   └── state
├── consensus
├── network
├── restAPI
└── utils
```

# state management point



* ```Public State```

  **Public State** stores state on to all peers(nodes)

* ```Channel State```

  **Channel State** store the state to the peers joined to the channel

* ```Private State```

  **Private State** stores state on specific peers(nodes)