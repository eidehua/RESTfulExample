# RESTfulExample
Sample restful example with Jetty (webserver) and Jersey

Restful requests 

@GET
	@Path("/getState")
	@Produces(MediaType.TEXT_PLAIN)
sp16-cs423-g07.cs.illinois.edu:8080/requests/getState


@GET
	@Path("/setThreshold/{threshold}")
	@Consumes(MediaType.TEXT_PLAIN)
sp16-cs423-g07.cs.illinois.edu:8080/requests/setThreshold/20

