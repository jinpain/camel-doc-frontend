<script>
	export let data;
	console.log(data.id)
</script>

<ul class="nav nav-tabs" id="docTab" role="tablist">
	<li class="nav-item" role="presentation">
		<button
			class="nav-link active"
			id="details-tab"
			data-bs-toggle="tab"
			data-bs-target="#details-tab-pane"
			type="button"
			role="tab"
			aria-controls="details-tab-pane"
			aria-selected="true">Реквизиты</button
		>
	</li>
	<li class="nav-item" role="presentation">
		<button
			class="nav-link"
			id="attachments-tab"
			data-bs-toggle="tab"
			data-bs-target="#attachments-tab-pane"
			type="button"
			role="tab"
			aria-controls="attachments-tab-pane"
			aria-selected="false">Вложения</button
		>
	</li>
</ul>
<div class="tab-content" id="docTabContent">
	<div
		class="tab-pane fade show active"
		id="details-tab-pane"
		role="tabpanel"
		aria-labelledby="details-tab"
		tabindex="0"
	></div>
	<div
		class="tab-pane fade"
		id="attachments-tab-pane"
		role="tabpanel"
		aria-labelledby="attachments-tab"
		tabindex="0"
	>
    <button class="btn btn-sm btn-secondary">Добавить</button>
 
    <table class="table table-sm table-hover">
        <thead>
            <tr>
                <th>Важное</th>
                <th>Наименование</th>
                <th>Дата создания</th>
                <th>Автор</th>
            </tr>
        </thead>
    </table>
	</div>
</div>
