<%= render layout: 'note', locals: { type: 'important' } do %>
  Be careful when using dynamic environment names. These names should be consistent and finite in number. If the environment name changes, data continuity will be broken for that environment.
<% end %>
