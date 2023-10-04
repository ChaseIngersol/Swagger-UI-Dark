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

Make a top-level `wwwroot/swagger-ui/` directory in your project and add `swagger_ui_dark.css` to it.
