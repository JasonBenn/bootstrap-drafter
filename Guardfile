guard :shell do
  watch 'draft.haml' do
    `haml draft.haml > draft.html`
  end
end

guard :livereload do
  watch(%r{draft.html})
end