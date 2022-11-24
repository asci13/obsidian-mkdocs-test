<%*let oldDashboardFile = await this.app.vault.getAbstractFileByPath("docs/Dataview/Services.md");

let dashboardTemplate = await this.app.vault.getAbstractFileByPath("Templates/Services.Markdown.md");

// DELETE CURRENT HOME PAGE

await this.app.vault.trash(oldDashboardFile);

// CREATE NEW HOME PAGE WITH UPDATED PROJECT TABLE

let newDashboardFolder = await this.app.vault.getAbstractFileByPath("docs/Dataview");

let newDashboardFile = await tp.file.create_new(dashboardTemplate, "Services", true, newDashboardFolder);
%>