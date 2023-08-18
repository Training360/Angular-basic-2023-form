# Angular-basic-2023-form
Template Driven Angular Forms

## Lesson-01
- Explaining the course.
- [TicketEditorComponent](src/app/ticket/ticket-editor/ticket-editor.component.ts)

## Lesson-02
- [Bt5 Card](https://getbootstrap.com/docs/5.3/components/card/#titles-text-and-links)
- [TicketEditorComponent HTML](src/app/ticket/ticket-editor/ticket-editor.component.html)
- [TicketEditorComponent SCSS](src/app/ticket/ticket-editor/ticket-editor.component.scss)

## Lesson-03
- [ConfigService](src/app/service/config.service.ts)
- [NavComponent](src/app/common/nav/nav.component.ts)

## Lesson-04
- Move the logic and the view from the AppComponent to the TicketsComponent.
- [AppComponent](src/app/app.component.ts)
- [TicketsComponent](src/app/page/tickets/tickets.component.ts)

## Lesson-05
- Set the routerLinkActive and the routerLinkActiveOptions directives.
- [NavComponent](src/app/common/nav/nav.component.ts)
- [NavComponent SCSS](src/app/common/nav/nav.component.scss)

## Lesson-06
- Generate a module: `ng generate module ticket --route ticket --module app.module`
- Shared module: `ng generate module shared --flat`
- Move the TicketsModule into the new ticket directory.
- Move all common directives, pipes into the shared module.
- Import shared module into the TicketModule.

## Lesson-07
- `ng g c ticket/ticket-editor --module ticket.module`
- [TicketRoutingModule](src/app/ticket/ticket-routing.module.ts)
- [TicketsComponent](src/app/page/tickets/tickets.component.ts)

## Lesson-08
- [AppRoutingModule](src/app/app-routing.module.ts)
- `imports: [RouterModule.forRoot(routes, {bindToComponentInputs: true})],`
- [TicketEditorComponent](src/app/ticket/ticket-editor/ticket-editor.component.ts)
  