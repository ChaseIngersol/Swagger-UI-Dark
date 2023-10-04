# Swagger UI Dark
A modern dark theme for Swagger UI based on [itz-fork/Fastapi](https://github.com/Itz-fork/Fastapi-Swagger-UI-Dark).

## Usage

### ASP.NET

In `Program.cs` or `Startup.cs`:

```
app.UseSwaggerUI(c => {
    c.InjectStylesheet("/swagger-ui/swagger_ui_dark.css");
});
```

```
app.UseStaticFiles();
```

Create a top-level `wwwroot/swagger-ui/` directory in your project and put the `swagger_ui_dark.css` in it.
