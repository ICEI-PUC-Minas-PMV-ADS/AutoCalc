# Instruções de utilização

## Instalação do Site

O site em HTML/CSS/JS é um projeto estático, logo pode ser utilizado tanto em servidores...

## Histórico de versões

### [0.1.0] - 11/05/2022

CRUD Abastecimento
Index

@model IEnumerable<AutoCalc.Models.Class2>

@{
    ViewData["Title"] = "Index";
}

<h1>Index</h1>

<p>
    <a asp-action="Create">Create New</a>
</p>
<table class="table">
    <thead>
        <tr>
            <th>
                @Html.DisplayNameFor(model => model.Data)
            </th>
            <th>
                @Html.DisplayNameFor(model => model.NomeDoPosto)
            </th>
            <th>
                @Html.DisplayNameFor(model => model.ValorPorLitro)
            </th>
            <th>
                @Html.DisplayNameFor(model => model.TotaldeLitrosABastecido)
            </th>
            <th>
                @Html.DisplayNameFor(model => model.ValorTotal)
            </th>
            <th>
                @Html.DisplayNameFor(model => model.KilometragemTotalDoVeiculo)
            </th>
            <th>
                @Html.DisplayNameFor(model => model.QualtipodeCombustivel)
            </th>
            <th></th>
        </tr>
    </thead>
    <tbody>
@foreach (var item in Model) {
        <tr>
            <td>
                @Html.DisplayFor(modelItem => item.Data)
            </td>
            <td>
                @Html.DisplayFor(modelItem => item.NomeDoPosto)
            </td>
            <td>
                @Html.DisplayFor(modelItem => item.ValorPorLitro)
            </td>
            <td>
                @Html.DisplayFor(modelItem => item.TotaldeLitrosABastecido)
            </td>
            <td>
                @Html.DisplayFor(modelItem => item.ValorTotal)
            </td>
            <td>
                @Html.DisplayFor(modelItem => item.KilometragemTotalDoVeiculo)
            </td>
            <td>
                @Html.DisplayFor(modelItem => item.QualtipodeCombustivel)
            </td>
            <td>
                <a asp-action="Edit" asp-route-id="@item.Id">Edit</a> |
                <a asp-action="Details" asp-route-id="@item.Id">Details</a> |
                <a asp-action="Delete" asp-route-id="@item.Id">Delete</a>
            </td>
        </tr>
}
    </tbody>
</table>



Criar

@model AutoCalc.Models.Class2

@{
    ViewData["Title"] = "Create";
}

<h1>Create</h1>

<h4>Class2</h4>
<hr />
<div class="row">
    <div class="col-md-4">
        <form asp-action="Create">
            <div asp-validation-summary="ModelOnly" class="text-danger"></div>
            <div class="form-group">
                <label asp-for="Data" class="control-label"></label>
                <input asp-for="Data" class="form-control" />
                <span asp-validation-for="Data" class="text-danger"></span>
            </div>
            <div class="form-group">
                <label asp-for="NomeDoPosto" class="control-label"></label>
                <input asp-for="NomeDoPosto" class="form-control" />
                <span asp-validation-for="NomeDoPosto" class="text-danger"></span>
            </div>
            <div class="form-group">
                <label asp-for="ValorPorLitro" class="control-label"></label>
                <input asp-for="ValorPorLitro" class="form-control" />
                <span asp-validation-for="ValorPorLitro" class="text-danger"></span>
            </div>
            <div class="form-group">
                <label asp-for="TotaldeLitrosABastecido" class="control-label"></label>
                <input asp-for="TotaldeLitrosABastecido" class="form-control" />
                <span asp-validation-for="TotaldeLitrosABastecido" class="text-danger"></span>
            </div>
            <div class="form-group">
                <label asp-for="ValorTotal" class="control-label"></label>
                <input asp-for="ValorTotal" class="form-control" />
                <span asp-validation-for="ValorTotal" class="text-danger"></span>
            </div>
            <div class="form-group">
                <label asp-for="KilometragemTotalDoVeiculo" class="control-label"></label>
                <input asp-for="KilometragemTotalDoVeiculo" class="form-control" />
                <span asp-validation-for="KilometragemTotalDoVeiculo" class="text-danger"></span>
            </div>
            <div class="form-group">
                <label asp-for="QualtipodeCombustivel" class="control-label"></label>
                <input asp-for="QualtipodeCombustivel" class="form-control" />
                <span asp-validation-for="QualtipodeCombustivel" class="text-danger"></span>
            </div>
            <div class="form-group">
                <input type="submit" value="Create" class="btn btn-primary" />
            </div>
        </form>
    </div>
</div>

<div>
    <a asp-action="Index">Back to List</a>
</div>

Editar

@model AutoCalc.Models.Class2

@{
    ViewData["Title"] = "Edit";
}

<h1>Edit</h1>

<h4>Class2</h4>
<hr />
<div class="row">
    <div class="col-md-4">
        <form asp-action="Edit">
            <div asp-validation-summary="ModelOnly" class="text-danger"></div>
            <input type="hidden" asp-for="Id" />
            <div class="form-group">
                <label asp-for="Data" class="control-label"></label>
                <input asp-for="Data" class="form-control" />
                <span asp-validation-for="Data" class="text-danger"></span>
            </div>
            <div class="form-group">
                <label asp-for="NomeDoPosto" class="control-label"></label>
                <input asp-for="NomeDoPosto" class="form-control" />
                <span asp-validation-for="NomeDoPosto" class="text-danger"></span>
            </div>
            <div class="form-group">
                <label asp-for="ValorPorLitro" class="control-label"></label>
                <input asp-for="ValorPorLitro" class="form-control" />
                <span asp-validation-for="ValorPorLitro" class="text-danger"></span>
            </div>
            <div class="form-group">
                <label asp-for="TotaldeLitrosABastecido" class="control-label"></label>
                <input asp-for="TotaldeLitrosABastecido" class="form-control" />
                <span asp-validation-for="TotaldeLitrosABastecido" class="text-danger"></span>
            </div>
            <div class="form-group">
                <label asp-for="ValorTotal" class="control-label"></label>
                <input asp-for="ValorTotal" class="form-control" />
                <span asp-validation-for="ValorTotal" class="text-danger"></span>
            </div>
            <div class="form-group">
                <label asp-for="KilometragemTotalDoVeiculo" class="control-label"></label>
                <input asp-for="KilometragemTotalDoVeiculo" class="form-control" />
                <span asp-validation-for="KilometragemTotalDoVeiculo" class="text-danger"></span>
            </div>
            <div class="form-group">
                <label asp-for="QualtipodeCombustivel" class="control-label"></label>
                <input asp-for="QualtipodeCombustivel" class="form-control" />
                <span asp-validation-for="QualtipodeCombustivel" class="text-danger"></span>
            </div>
            <div class="form-group">
                <input type="submit" value="Save" class="btn btn-primary" />
            </div>
        </form>
    </div>
</div>

<div>
    <a asp-action="Index">Back to List</a>
</div>

@section Scripts {
    @{await Html.RenderPartialAsync("_ValidationScriptsPartial");}
}


Deletar
@{
    ViewData["Title"] = "Delete";
}

<h1>Delete</h1>

<h3>Are you sure you want to delete this?</h3>
<div>
    <h4>Class2</h4>
    <hr />
    <dl class="row">
        <dt class = "col-sm-2">
            @Html.DisplayNameFor(model => model.Data)
        </dt>
        <dd class = "col-sm-10">
            @Html.DisplayFor(model => model.Data)
        </dd>
        <dt class = "col-sm-2">
            @Html.DisplayNameFor(model => model.NomeDoPosto)
        </dt>
        <dd class = "col-sm-10">
            @Html.DisplayFor(model => model.NomeDoPosto)
        </dd>
        <dt class = "col-sm-2">
            @Html.DisplayNameFor(model => model.ValorPorLitro)
        </dt>
        <dd class = "col-sm-10">
            @Html.DisplayFor(model => model.ValorPorLitro)
        </dd>
        <dt class = "col-sm-2">
            @Html.DisplayNameFor(model => model.TotaldeLitrosABastecido)
        </dt>
        <dd class = "col-sm-10">
            @Html.DisplayFor(model => model.TotaldeLitrosABastecido)
        </dd>
        <dt class = "col-sm-2">
            @Html.DisplayNameFor(model => model.ValorTotal)
        </dt>
        <dd class = "col-sm-10">
            @Html.DisplayFor(model => model.ValorTotal)
        </dd>
        <dt class = "col-sm-2">
            @Html.DisplayNameFor(model => model.KilometragemTotalDoVeiculo)
        </dt>
        <dd class = "col-sm-10">
            @Html.DisplayFor(model => model.KilometragemTotalDoVeiculo)
        </dd>
        <dt class = "col-sm-2">
            @Html.DisplayNameFor(model => model.QualtipodeCombustivel)
        </dt>
        <dd class = "col-sm-10">
            @Html.DisplayFor(model => model.QualtipodeCombustivel)
        </dd>
    </dl>
    
    <form asp-action="Delete">
        <input type="hidden" asp-for="Id" />
        <input type="submit" value="Delete" class="btn btn-danger" /> |
        <a asp-action="Index">Back to List</a>
    </form>
</div>

