# Denarius

Open-source financial exchange software.

## Status

- A matching engine that implements market and limit orders.
- An HTTP/JSON backend server for receiving oders

## ToDo (Immediately)

- Asset properties handling
- Customer/Broker Desks account handling

## Dependencies

- Aleph/Lamina/Gloss
- JSON (data.json)
- Log (tools.logging)

## Usage

Currently there are no binaries to this software.

To try out Denarius, start a development server with:

```Bash
lein run
```

Then send orders to the server with the utility client ([See Wiki](https://github.com/analyticbastard/denarius/wiki/Taste-it:-Interactive-order-entry-command-line))

```Bash
lein -m util.client/-main
```

If you want to make your own client API, you can foolow the code in the
utility client.

The server now informs about (partial) order execution, on every execution
it makes, with the communications channel registered upon order entry. 


## Contact

Mailing list (important announcements): denarius@librelist.com

General announcements: http://machinomics.blogspot.com

## License

Copyright © 2013 Javier Arriero-Pais

Distributed under the MIT License.
