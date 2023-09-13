library(arrow)
library(shiny)

ui <- fluidPage(
  titlePanel("Test App"),
  sidebarLayout(
    mainPanel(
      renderText("Hello Test")
    )
  )
)
server <- function(input, output) {
  print("test server")
}

# Run the application 
shinyApp(ui = ui, server = server)